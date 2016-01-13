#### Test 55902202f27eba5_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
,E/cutils-trace( 4499): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4499): ====startRecUseTime====
D/htc.customization.log.level( 4499):  is 
W/CustomizationLogLevel( 4499): Level value is invalid, use default level 2
D/CustomizationManager( 4499):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4499): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4499): Parsing tag category name = system
I/CustomizationCIDLoader( 4499): Parsing tag category name = application
I/CustomizationCIDLoader( 4499): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4499): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4499): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4499): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4499): Parsing tag category name = Settings
D/CustomizationManager( 4499):  Read CID file spent 0.105 (s)
D/CustomizationManager( 4499):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4499): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4499): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4499): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4499): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4499
D/PMS     (  909): acquireHCC(42729a18): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(4240a620): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
W/asset   (  909): Copying FileAsset 0x62aba9b8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1112968176
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@421c5948
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
D/PMS     (  909): acquireWL(42470ba8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4510 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1274): [trimMemory] 20
W/asset   ( 4510): Copying FileAsset 0x5c858428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4510): Binding Chromium to main looper Looper (main, tid 1) {41ad2ed0}
I/LibraryLoader( 4510): Expected native library version number "",actual native library version number ""
I/chromium( 4510): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4510): Initializing chromium process, renderers=0
D/PMS     (  909): acquireWL(424b3060): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): acquireWL(425bbff0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): releaseWL(424b3060): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425f8bb8:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4510): 1101962824: getState(). Returning 12
I/ActivityManager(  909): Waited long enough for: ServiceRecord{4237ccc0 u0 com.htc.htclocationservice/.AutoSettingService}
I/Adreno-EGL( 4510): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4510): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4510): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4510): Local Branch: 
I/Adreno-EGL( 4510): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4510): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4510):                  aa63bbd948f41d15fc72f585e
W/chromium( 4510): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4510): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4510): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4510): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4510): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4510): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4510): CordovaWebView is running on device made by: HTC
,W/AwContents( 4510): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Disable input method client, pid=1274
,W/ResourceType( 4510): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4510): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b1b4f8, mServedView=org.apache.cordova.engine.SystemWebView{41ae1160 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  909): Enable input method client, pid=4510
W/AwContents( 4510): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +299ms
,D/PMS     (  909): releaseWL(42470ba8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4510): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4510): JniHelper::setJavaVM(0x415a9048), pthread_self() = 1663284584
,D/JX-Cordova( 4510): jxcore cordova android initializing
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.546MB for 63974-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.601MB for 95956-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.681MB for 143930-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.797MB for 215890-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.967MB for 323830-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 12.629MB for 728606-byte allocation
,I/SensorManager(  909): mEventCount = 1200
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 13.226MB for 1092904-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 14.135MB for 1639352-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 15.481MB for 2459024-byte allocation
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(42729a18): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(4240a620): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 17.591MB for 3688532-byte allocation
,W/jxcore-log( 4510): Initializing JXcore engine
,W/jxcore-log( 4510): JXcore engine is ready
,W/jxcore-log( 4510): Starting JXcore engine
,W/jxcore-log( 4510): Platform android
W/jxcore-log( 4510): 
,W/jxcore-log( 4510): Process ARCH arm
W/jxcore-log( 4510): 
,I/jxcore-log( 4510): JXcore Cordova bridge is ready!
I/jxcore-log( 4510): 
,W/jxcore-log( 4510): JXcore engine is started
,I/chromium( 4510): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  909): releaseWL(425bbff0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4510): Toggling radios to true
I/jxcore-log( 4510): 
,D/BluetoothAdapter( 4510): enable(): BT is already enabled..!
,D/WifiManager( 4510): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  909): New client listening to asynchronous messages
,W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 2
W/Settings:Agent(  909): >> traceCallingStack()
,W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1373
,W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
,W/Settings:Agent(  909): 
,W/System.err(  909): java.lang.Throwable: stack dump
,W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
,W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  909): 
,W/Settings:Agent(  909): << traceCallingStack(): 7(ms)
D/WifiService(  909): setWifiEnabled: true pid=4510, uid=10389
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
D/WifiManager( 4510): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  909): doBoolean: DISCONNECT
D/WifiManager( 4510): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1161): TDLS: Tear down peers
I/wpa_supplicant( 1161): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4510): Radios toggled
I/jxcore-log( 4510): 
I/jxcore-log( 4510): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4510): 
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1161): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1161): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1161): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8b00bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1161):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1161): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
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
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
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
D/w,pa_supplicant( 1161): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1161): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiNative-wlan0(  909):    returned true
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiPerfLock(  909): release()
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  909): acquireWL(440c6a70): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0",
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/Tethering(  909): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
D/DhcpStateMachine(  909): [RunningState] Stop DHCP
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909): doBoolean: RECONNECT
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
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
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19854 mDataStallAlarmIntent=PendingIntent{424819e0: PendingIntentRecord{425ee2b8 android broadcastIntent}}
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WISPrService( 3849): >>>>>WISPrService start isConnected = false<<<<<
D/UsbnetStateTracker(  909): isAvailable+-
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS,
,D/WISPrService( 3849): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiService(  909): New client listening to asynchronous messages
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 3849): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3849): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1342): Read error: ssl=0x66069740: I/O error during system call, Connection timed out
,V/NativeCrypto( 1342): SSL shutdown failed: ssl=0x66069740: I/O error during system call, Broken pipe
D/libc    (  364): [NET] entry_id:3   entry:0xb7c618e0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7c66190  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7c66348  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7c66428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7c66090  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7c664f0  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7c61fe8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/PMS     (  909): acquireWL(425c8af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(434ddf40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN",
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  909):    returned false
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
D/BatSI   (  909): WIFI scan started for: 650a0300 uid:1000
,D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1342/10029)
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/PMS     (  909): releaseWL(434ddf40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,D/PMS     (  909): releaseWL(425c8af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421bb010
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  909): pid=909, uid=1000
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  909): Couldn't get kernel wake lock stats
W/SensorService(  909): Active sensors: size = 2
,W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421bb010, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4204f470
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@4217f590
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  909): mWirelessDisplayManager is null
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  909): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4563 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(440ca158): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(440ca158): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4322/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4322/10100)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 313ms
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
D/PMS     (  909): OOBE c monitor 11
D/NfcService( 1253): ScreenObserver: OFF
D/NfcService( 1253): applyRouting - 0
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1253): applyRouting -2
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43703be8)
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=4510
D/PMS     (  909): acquireWL(4364da88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  909): releaseWL(4364da88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/PMN     (  909): wakingUp
I/WindowManager(  909): No lock screen! windowToken=null
,D/PMS     (  909): acquireWL(440bc258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/PMN     (  909): onScreenOn
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(440bc258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/MtpService( 2351): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2351): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): acquireWL(4372ea28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  909): releaseWL(4372ea28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:On
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
I/MusicStore( 4563): Database version: 95
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SET pno 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 1161): wpa_supplicant_scan enter
,D/WifiNative-wlan0(  909):    returned true
,W/ContextImpl( 4563): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/HtcPowerSaver(  909): << updateStatus
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,I/ClockThread( 1116): stop update clock
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
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
,W/ContextImpl( 4563): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4563): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): acquireWL(43840bf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(43840bf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(426cb720): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4563): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4563): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/PMS     (  909): releaseWL(426cb720): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1742): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): onScreenOn: 1452699347264
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1742): onScreenOn: 1452699347264
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4563, uid=10154, userID:0
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4204f470
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4204f470, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@4217f590
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(44252858): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19855 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  909): doBoolean: SET pno 1
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
,D/PMS     (  909): acquireWL(44113970): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:Off
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1161): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1161): get_ip_address source addr = 02000000
I/wpa_supplicant( 1161): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): CTRL_IFACE SET 'pno'='1'
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
D/MediaRouterService(  909): Client com.google.android.music (pid 4563): Registered
D/NetworkPolicy(  909): updateScreenOn: false
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,I/MediaRouter( 4563): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1161): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
D/wpa_supplicant( 1161): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/WifiNative-wlan0(  909):    returned true
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 3
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 1
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): selected network = 2
D/wpa_supplicant( 1161): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8b024e8  current_ssid=0x0
D/wpa_supplicant( 1161): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1161): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1161): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1161): check if in concurrent case
I/wpa_supplicant( 1161): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1161): RSN: PMKSA cache search - network_ctx=0xb8b024e8 try_opportunistic=0
D/wpa_supplicant( 1161): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 1161): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1161): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1161): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1161): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1161): nl80211: Unsubscribe mgmt frames handle 0xb8b01718 (mode change)
D/wpa_supplicant( 1161): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8b01718
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718,
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8b01718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1161): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1161):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1161):   * freq=2412
D/wpa_supplicant( 1161):   * Auth Type 0
D/wpa_supplicant( 1161):   * WPA Versions 0x2
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1161): nl80211: Connect request send successfully
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): releaseWL(44113970): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000021959994
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-54
I/wpa_supplicant( 1161): tsf=0000000021960065
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-54
I/wpa_supplicant( 1161): tsf=0000000104251580
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-82
I/wpa_supplicant( 1161): tsf=0000000021960075
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 21959994, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 21960065, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 104251580, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 21960075, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2351/10021)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.music (4563/10154)
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4589 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] getTotalRam: 1873 Mb
,D/MediaRouter( 4563): getSelectedRoute
,I/NetworkMonitor( 4563): type=WIFI subType= reason=null isConnected=false
D/PMS     (  909): acquireWL(4367c718): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4367c718): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4563/10154)
D/PMS     (  909): acquireWL(425a28b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1742): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1742): onScreenOff
D/PMS     (  909): releaseWL(425a28b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ACRA    ( 4589): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4589): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4589): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4563, uid=10154, userID:0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/Process (  909): killProcessQuiet, pid=4109
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  909): acquireWL(42c586b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(42c586b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  909): Killing 4109:com.google.android.talk/u0a111 (adj 15): empty #17
,D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
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
D/wpa_supplicant( 1161): Add randomness: count=8 entropy=1
I/wpa_supplicant( 1161): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1161): TDLS: Remove peers on association
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
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
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor,(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
I/wpa_supplicant( 1161): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1161): Get randomness: len=32 entropy=2
D/WifiStateMachine(  909): Associated
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
W/SystemClassLoaderAdder( 4589): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
V/DexLibLoader( 4589): Preparing secondary program dexes.
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/DexLibLoader( 4589): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4589): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
I/wpa_supplicant( 1161): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
V/DexLibLoader( 4589): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8b019f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1161):    addr=c0:ff:d4:d3:aa:48
V/DexLibLoader( 4589): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4589): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 11
D/WifiApDatabaseHandler(  909): updateConnectedAP...
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1161): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f96b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1161):    broadcast key
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1161): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1161): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1161): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1161): wlan0: Connect to SSID: NG700
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
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
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1161): EAPOL authentication completed successfully
I/wpa_supplicant( 1161): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
W/DexLibLoader( 4589): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
V/DexLibLoader( 4589): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4589): Dex already copied
D/OdexVerifier( 4589): Odex verification is skipped.
V/DexLibLoader( 4589): Creating class loader
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/Tethering(  909): [isWifi] getHotspotEnabled: false
V/DexLibLoader( 4589): Finished creating class loader
V/DexLibLoader( 4589): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4589): Dex already copied
D/OdexVerifier( 4589): Odex verification is skipped.
V/DexLibLoader( 4589): Creating class loader
V/DexLibLoader( 4589): Finished creating class loader
V/DexLibLoader( 4589): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4589): Dex already copied
D/OdexVerifier( 4589): Odex verification is skipped.
V/DexLibLoader( 4589): Creating class loader
V/DexLibLoader( 4589): Finished creating class loader
V/DexLibLoader( 4589): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4589): Dex already copied
D/OdexVerifier( 4589): Odex verification is skipped.
V/DexLibLoader( 4589): Creating class loader
V/DexLibLoader( 4589): Finished creating class loader
V/DexLibLoader( 4589): Verifying classes from secondary dexes.
D/DexLibLoader( 4589): DexLibLoader.ensureDexLoaded took 22 ms
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
I/ActivityManager(  909): Recipient 4109
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  909): Provision feature enable=false
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/WISPrService( 3849): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3849): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiNative-wlan0(  909): doBoolean: SET pno 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1161): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  909):    returned true
D/DhcpStateMachine(  909): [StoppedState] Start DHCP
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 1
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET,
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET",
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null,
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  909):    returned null
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0,
,D/wpa_supplicant( 1161): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(42344930): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425661c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425661c0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,W/ActivityManager(  909): Activity pause timeout for ActivityRecord{41cf8070 u0 com.test.thalitest/.MainActivity t2}
,W/dalvikvm( 4589): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4589): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4589): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4589): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4589): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4589): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4589): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4589): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1161): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1161): EAPOL: disable timer tick
,W/dalvikvm( 4589): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4589): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4589): Verify
,D/WifiService(  909): New client listening to asynchronous messages
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4589): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4589): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4589): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,I/ActivityManager(  909): Killing 4290:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4290
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  909): Recipient 4290
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4619 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/AutoSetting( 1332): Util - no network available!
,D/AutoSetting( 1332): service - onCreate()
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/AutoSetting( 1332): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  909): request 42588238 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1332): service - mHandler: cancel location update
,D/AutoSetting( 1332): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4589): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4589): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4589): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/MobileConnectivityChangeReceiver( 4619): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4619): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4619): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4619): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  909): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4639 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4619/10079)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4619/10079)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4619/10079)
,I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4669 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=4322
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 4322:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4322
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/dalvikvm-heap( 4589): Grow heap (frag case) to 9.961MB for 84664-byte allocation
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  909): releaseWL(42344930): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [3][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,W/GAV2    ( 4669): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/WifiStateMachine(  909): gateway: /192.168.1.1
D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
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
I/dalvikvm-heap( 4589): Grow heap (frag case) to 9.978MB for 28144-byte allocation
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
E/dalvikvm( 4589): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4589): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/dalvikvm( 4589): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4589): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,W/ContextImpl( 4669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
E/dalvikvm( 4589): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4589): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,D/WifiWatchdogStateMachine(  909): WAN detection
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
E/dalvikvm( 4589): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4589): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4589): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4589): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4589): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4589): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4589): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4589): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4589): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4589): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4589): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4589): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/WISPrService( 3849): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@4245cc48
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(43b87420): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
I/dalvikvm-heap( 4589): Grow heap (frag case) to 10.045MB for 39954-byte allocation
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4619/10079)
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  909): acquireWL(41e46798): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(424d0738): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2182): Checkin interval check for package: unspecified last checkin: 1452699302453 min interval config: 0 actual interval: 46804
,D/PMS     (  909): releaseWL(41e46798): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2182): Checking schedule, now: 1452699349262 next: 1452699332398
,I/CheckinService( 2182): active receiver: enabled
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/dalvikvm-heap( 4589): Grow heap (frag case) to 10.122MB for 79892-byte allocation
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
,D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,I/CheckinService( 2182): Preparing to send checkin request
,I/EventLogService( 2182): Accumulating logs since 1452699297968
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(43b87420): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4669/10151)
,I/CheckinRequestBuilder( 2182): Checkin reason type: 8 attempt count: 1
,V/WebViewChromiumFactoryProvider( 4669): Binding Chromium to main looper Looper (main, tid 1) {41ad9138}
I/LibraryLoader( 4669): Expected native library version number "",actual native library version number ""
I/chromium( 4669): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4669): Initializing chromium process, renderers=0
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2182): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  909): acquireWL(423f4f98): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4669): BLUETOOTH permission is missing!
D/PMS     (  909): acquireWL(42d78ac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): releaseWL(423f4f98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4669): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4669): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4669): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4669): Local Branch: 
I/Adreno-EGL( 4669): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4669): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4669):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4589): Grow heap (frag case) to 10.284MB for 75760-byte allocation
,I/NSApplication( 4669): Starting up...
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4669/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4669/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42d49090 u0 ReceiverList{42d41010 4589 com.facebook.katana/10027/u0 remote:42722d80}}
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42d49090 u0 ReceiverList{42d41010 4589 com.facebook.katana/10027/u0 remote:42722d80}}
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44112668 u0 ReceiverList{44112628 4589 com.facebook.katana/10027/u0 remote:440c7bf0}}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4151/10160)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/Process (  909): killProcessQuiet, pid=4347
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4151/10160)
I/ActivityManager(  909): Killing 4347:com.htc.backup/1000 (adj 15): empty #17
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
I/ActivityManager(  909): Recipient 4347
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2182/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4719 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  909): acquireWL(4258a940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4258a940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4589): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4589): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4589): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4719): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  909): acquireWL(44206d48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4719 1000 null
,D/SmartSyncUtils( 4719): isEpsOn(), nState = 0
,D/PMS     (  909): releaseWL(44206d48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4742 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1332): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3849): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3849): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3849): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3849): Cust_ConnectToPC   : spcsc>false
D/        ( 3849): Cust_ConnectToPC   : IPT>true
D/        ( 3849): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3849): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3849): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3849): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3849): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3849): onReceive:android.intent.action.USER_PRESENT
,D/SmartSyncUtils( 4719): getMobilePolicyEnabled, result = true
W/ContextImpl( 3849): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/dalvikvm( 4742): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
I/SmartNS_PSService( 3849): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3849): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3849):  defaultType:0
,W/dalvikvm( 4742): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4742): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4742): install
,I/MultiDex( 4742): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/Process (  909): killProcessQuiet, pid=4308
,I/ActivityManager(  909): Killing 4308:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/MultiDex( 4742): loading existing secondary dex files
I/MultiDex( 4742): load found 3 secondary dex files
,I/MultiDex( 4742): install done
I/ActivityManager(  909): Recipient 4308
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4742): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4742): VFY: unable to resolve instance field 36
,W/dalvikvm( 4742): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/ContextImpl( 4719): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4719): isEpsOn(), nState = 0
D/SmartSyncUtils( 4719): isEpsOn(), nState = 0
D/SmartSyncUtils( 4719): getMobilePolicyEnabled, result = true
,V/JNIHelp ( 4742): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/WifiService(  909): New client listening to asynchronous messages
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4217f590
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4217f590, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4217f590, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4217f590
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42399bf8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42399bf8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/ProviderInstaller( 4742): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4742): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4742): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,W/dalvikvm( 4742): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4742): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4742): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4742): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4742): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/MDM     ( 1222): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2182): Restart initialization of location
,D/AuthorizationBluetoothService( 1342): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1342): Proximity feature is not enabled.
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  909): acquireWL(42d5b8d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(42d5b8d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4742): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3687893723
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/PMS     (  909): releaseWL(440c6a70): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/CaptivePortalTracker(  909): NoActiveNetworkState
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
,V/Tethering(  909): bSetPropertyMultiRAB:false
D/AccTypeManager( 1358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(42668d08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 4563): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4563/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4619/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3948/10053)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
D/PMS     (  909): acquireWL(436ade70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/PMS     (  909): releaseWL(436ade70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(42668d08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027),
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
,W/AccTypeManager( 1358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2351/10021)
,W/Settings( 4742): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/ExternalAccountType( 1358): Unsupported attribute readOnly
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4619): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4619): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1332): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4669/10151)
,D/AutoSetting( 1332): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1332): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4151/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4151/10160)
,D/PMS     (  909): acquireWL(441f4ac8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2182): Checkin interval check for package: unspecified last checkin: 1452699302453 min interval config: 0 actual interval: 47937
,D/PMS     (  909): releaseWL(441f4ac8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/dalvikvm-heap( 4151): Grow heap (frag case) to 13.509MB for 1821008-byte allocation
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  371): CdmEngine::OpenSession
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1341848355
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4742/10029)
,I/CheckinRequestBuilder( 2182): Classify the device as Phone.
,D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2182): [NET] getaddrinfo-,err=8
D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2182): [NET] getaddrinfo-, 1
,D/libc    ( 2182): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =62e5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 268,
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2,
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2182): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2182): [NET] getaddrinfo-,err=8
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2182): [NET] getaddrinfo-,err=8
D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2182): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2182): Sending checkin request (12190 bytes)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
,W/fb4a(:<default>):UserScope( 4589): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4589): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=23 [17][4][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
,I/CheckinRequestBuilder( 2182): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2182): Failed to find provider info for com.google.android.wearable.settings
,E/fb4a(:<default>):LocalFbBroadcastManager( 4589): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2182/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [3][0][0]
,I/CheckinRequestBuilder( 2182): Classify the device as Phone.
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
,I/CheckinTask( 2182): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2182): Checking schedule, now: 1452699352018 next: 1453222289012
I/CheckinService( 2182): active receiver: disabled
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
I/CheckinService( 2182): Checking schedule, now: 1452699352039 next: 1453222289012
,I/CheckinService( 2182): active receiver: disabled
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
D/CheckinService( 2182): Recording last checkin time for package unspecified as 1452699352045
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/PMS     (  909): releaseWL(424d0738): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4589/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/PMS     (  909): acquireWL(42685f40): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
D/GCM     ( 1342): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1342): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    ( 1342): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1342): [NET] getaddrinfo-, 1
D/libc    ( 1342): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ef9f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 146
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1342): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1342): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
,D/libc    ( 1342): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =52ff +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/72.247.98.119
,W/ActivityManager(  909): Sleep timeout!  Sleeping now.
,D/PMS     (  909): releaseWL(44252858): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  909): acquireWL(43cd39c8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4563 10154 null
,D/PMS     (  909): acquireWL(42d0a1c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4563): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,D/PMS     (  909): releaseWL(42685f40): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42d78ac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1342/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4563, uid=10154, userID:0
,D/PMS     (  909): releaseWL(42d0a1c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(441c5170): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,I/MusicLeanback( 4563): Conditions not met for autocaching.
,I/MusicLeanback( 4563): Stop autocaching.
D/PMS     (  909): releaseWL(43cd39c8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1342/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,W/ContextImpl( 4563): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1342/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
D/PMS     (  909): releaseWL(441c5170): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=18 [11][2][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4669): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4510): Test app app.js loaded
I/jxcore-log( 4510): 
,I/Choreographer( 4510): Skipped 519 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4510): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4510): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4510): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ae1160 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  909): killProcessQuiet, pid=4365
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4365:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4365
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=4396
,I/ActivityManager(  909): Killing 4396:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/AutoSetting( 1510): service - handleMessage() quit looper
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4396
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  909): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4803 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/AccTypeManager( 1358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsUpdated
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1358): Unsupported attribute readOnly
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4803): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4803): MmsConfig.loadMmsSettings
,W/dalvikvm( 4803): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4803): VFY: unable to resolve instance field 36
,W/dalvikvm( 4803): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4803): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  909): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4826 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,D/MessageFrequencyProvider( 4826): onCreate
,V/GetPrviateResource( 4826): GetPrviateResource
D/MmsCustomizationProvider( 4826): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4826): GetPrviateResource
,D/MmsCustomizationProvider( 4826): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4803, uid=10111, userID:0
,I/Babel   ( 4803): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4803): MmsConfig.loadFromDatabase
,W/PackageManager(  909): Unable to load service info ResolveInfo{434e9d58 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,W/Settings( 4803): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AutoSetting( 1332): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1332): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1332): service - requestNLP() NetworkLocationProvider not enabled
E/Babel   ( 4803): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4803): MmsConfig.loadFromResources
,E/Babel   ( 4803): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4803): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4803, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4803, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4803, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4803, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4803, uid=10111, userID:0
D/PMS     (  909): acquireWL(437e6528): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4803 10111 null
,I/ProviderInstaller( 4803): Installed default security provider GmsCore_OpenSSL
I/[PluginManager]RegisterService( 1332): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1332): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/IcingCorporaProvider( 2853): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/MessageCustFlag( 4826): sense_version=6.0
D/BTAccessoryUtil( 4826): createReceiver
D/BTAccessoryUtil( 4826): registerReceiver return intent = null
D/MessageCustFlag( 4826): sku_id=99
W/SystemReader( 4826): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4826): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4826): networkCode: 
,D/MessageCustFlag( 4826): sku_id=99
D/MmsConfig( 4826): SIE smsPri: null
,D/MmsConfig( 4826): networkCode: 
,D/PMS     (  909): acquireWL(42c23af0): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
D/HtcTelephonyCapability( 4826): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4826): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4826): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4826): Cannot find qct_8960_interface, use default value instead
D/PMS     (  909): releaseWL(42c23af0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(437e6528): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  909): killProcessQuiet, pid=4417
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  909): acquireWL(43c11850): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): Killing 4417:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/WifiService(  909): Client connection lost with reason: 4
I/ActivityManager(  909): Recipient 4417
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): releaseWL(43c11850): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  909): acquireWL(42664628): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42664628): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  909): acquireWL(42599340): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4151): Grow heap (frag case) to 15.210MB for 1821008-byte allocation
D/PMS     (  909): acquireWL(41bfd750): PARTIAL_WAKE_LOCK  AsyncService 0x1 4151 10160 null
,D/PMS     (  909): releaseWL(42599340): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4151): Grow heap (frag case) to 16.945MB for 1821008-byte allocation
D/PMS     (  909): acquireWL(42685830): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4364f888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{41ad5560: PendingIntentRecord{42327f98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=116948, Int=0
D/PMS     (  909): releaseWL(41bfd750): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4364f888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): releaseWL(42685830): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(4411e428): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/LocationProviderProxy(  909): applying state to connected service
D/PMS     (  909): acquireWL(424b01a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4411e428): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(424b01a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): Resuming delayed broadcast
,D/LocationProviderProxy(  909): applying state to connected service
I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
D/PMS     (  909): acquireWL(4356e928): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4382e380): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4382e380): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(43bbec38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(43bbec38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(426b82c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(426b82c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4356e928): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  909): acquireWL(42c2f628): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42c2f628): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(43c3d548): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2182): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2182): Null package name or gms related package.  Ignoreing.
D/PMS     (  909): releaseWL(43c3d548): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4372bd70): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2182): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2853): UpdateCorporaTask done [took 447 ms] updated apps [took 447 ms] 
I/ActivityManager(  909): Resuming delayed broadcast
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b66d78 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b66d78 -
,I/Icing   ( 2182): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2182): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  909): releaseWL(4372bd70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,D/Messaging( 4826): mNeedToUpdateDate2 start
,D/MmsConfig( 4826): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4826): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4826): 
D/MmsAsyncWorkHandler( 4826): HM tk = 20001
,D/ReportIndicatorCache( 4826): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4826): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41adb520
,I/Messaging( 4826): mccmnc> 
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1243):  phoneType = -1
D/DraftCache( 4826): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4826): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4826): networkCode: 
,D/Messaging( 4826): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 4826): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4826): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4826): createReceiver
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1243): sku_id=99
,D/MessageCustFlag( 4826): sense_version=6.0
,D/Jerry   ( 4826): start to preload cursor >>>>>>>
,D/TelephUtils( 1243): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,V/MmsProvider( 1243): Update uri=content://mms, match=0
,V/MmsProvider( 1243): selection=st=129 AND m_type!=134
,D/Messaging( 4826): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4826): TransactionService is going to be woken up.
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4826): [DraftCache/481] rebuildCache
,V/TransactionService( 4826): 1-Creating TransactionService
,V/TransactionService( 4826): onStartCommand: 1
,D/MmsSystemEventReceiver( 4826): unRegisterForConnectionStateChanges
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1243):  phoneType = -1
V/TransactionService( 4826): 4-Handling incoming message: { when=-2ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4826): Loading previous transactions.
,D/Messaging( 4826): mNeedToUpdateDate2: false
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1243): device_type: 1
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1243):  phoneType = -1
D/Messaging( 4826): ViewCache CreatePreload
D/Messaging( 4826): ViewCache CreatePreloadOnlyMultipleOpsList
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/TransactionService( 4826): Force set service start id to 1
V/TransactionService( 4826): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4826): unRegisterForConnectionStateChanges
,D/TransactionService( 4826): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4826): Destroying TransactionService
,D/Cust_MMSMS( 4826): _has_set_default_values_2=true
,V/TransactionService( 4826): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/Jerry   ( 1243): URI_DRAFT
,D/DraftCache( 4826): hasDraft() = false mNeedNotifyChange = true
,D/MsgPreferenceUtils( 4826): def_index: 0
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/DraftCache( 4826): [DraftCache/481] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4826): 
D/MmsAsyncWorkHandler( 4826): HM tk = 20002
,D/MsgPreferenceUtils( 4826): globalIndex = 1
D/MsgPreferenceUtils( 4826): phone state: true
D/MsgPreferenceUtils( 4826): sd state: false
,D/MsgPreferenceUtils( 4826): vIndex = 0
,D/Messaging( 4826): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1243): sku_id=99
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1243): sku_id=99
,D/Process (  909): killProcessQuiet, pid=3948
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3948:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3948
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{437c0600 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4803): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(42c6e3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42c6e3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(42f52810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{41e1e8b0: PendingIntentRecord{426d11c0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123824, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{42da98c0: PendingIntentRecord{426bf660 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134351, Int=0
,D/PMS     (  909): acquireWL(42e4dc70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=14 [14][2][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(42f1bc88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42f1bc88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42e4dc70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42f52810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(441cf0b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): releaseWL(441cf0b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42dbe398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): acquireWL(42e4bd10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(434f7f78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1452699377683 tag=VacuumService
,D/PMS     (  909): releaseWL(42dbe398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43fde5e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): releaseWL(43fde5e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(434f7f78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(434f02c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42e4bd10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): releaseWL(434f02c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(441253c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): releaseWL(441253c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(44085f90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): releaseWL(44085f90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1332): service - mHandler: update timezone
,D/AutoSetting( 1332): service - handleMessage() stop self
,D/AutoSetting( 1332): service - handleMessage() quit looper
,D/AutoSetting( 1332): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=4438
,I/ActivityManager(  909): Killing 4438:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,I/ActivityManager(  909): Recipient 4438
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1510): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1510): service - mHandler: update timezone
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1510): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1510): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c30258 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 7 3 11
,D/PMS     (  909): acquireWL(42c124f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d25e0: PendingIntentRecord{423e0e70 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141383, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(4382cca0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(42c124f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f351 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 43
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  909): releaseWL(4382cca0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{434da1e8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  909): acquireWL(4324cb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(4324cb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4452
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Killing 4452:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4452
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(4257f4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10027}
,V/AlarmManager(  909): sending alarm PendingIntent{43949058: PendingIntentRecord{438048e0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175454, Int=0
,D/PMS     (  909): releaseWL(4257f4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  909): acquireWL(434db278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ad5560: PendingIntentRecord{42327f98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=176949, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(434db278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(440043b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{436e82e8: PendingIntentRecord{426d11c0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=183843, Int=0
,D/PMS     (  909): releaseWL(440043b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4364fb00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=10 [48][5][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(42d565c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4364fb00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42d565c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4376ae70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): releaseWL(4376ae70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(436ed670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(42bca7e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(436ed670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 3564 seconds from now (1452699427691)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7139 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 175,
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=25 [12][3][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=50 [2][1][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): releaseWL(42bca7e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43cb8da8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): releaseWL(43cb8da8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43cb8d08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1342/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023913
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024258
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024263
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024267
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025837
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025878
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028777
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030365
,D/PMS     (  909): releaseWL(43cb8d08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43c895d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43c895d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43c2a918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c2a918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/ClearcutLoggerApiImpl( 1342): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(425fc008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ad5560: PendingIntentRecord{42327f98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=236949, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(425fc008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(423a5a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423a5a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(4248d0a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4248d0a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42426970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ad5560: PendingIntentRecord{42327f98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=296949, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42426970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(41e34e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(41e34e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4510): --= Surplus to requirements =--
I/jxcore-log( 4510): 
I/jxcore-log( 4510): ****TEST TOOK:  ms ****
I/jxcore-log( 4510): 
,I/jxcore-log( 4510): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4510): 
,E/cutils-trace( 4922): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4922): ====startRecUseTime====
D/htc.customization.log.level( 4922):  is 
,W/CustomizationLogLevel( 4922): Level value is invalid, use default level 2
,D/CustomizationManager( 4922):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 4922): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4922): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4922): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4922): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4922): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4922): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4922): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 4922): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4922): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4922): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4922): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4922): Parsing tag category name = system
I/CustomizationCIDLoader( 4922): Parsing tag category name = application,
I/CustomizationCIDLoader( 4922): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4922): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4922): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4922): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4922): Parsing tag category name = Settings
,D/CustomizationManager( 4922):  Read CID file spent 0.159 (s)
,D/CustomizationManager( 4922):  All configurations done spent 0.159 (s),
W/HtcNativeFlag( 4922): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4922): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4922): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4922): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4922, uid=2000 user=0
,I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  909): killProcessQuiet, pid=4510
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  909): Killing 4510:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  909):   Force finishing activity ActivityRecord{41cf8070 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  909): Copying FileAsset 0x63330af0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1210): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 4510 uid 10389
,W/PackageSettings(  909): Skipping PackageSetting{421b4f98 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  909): WIN DEATH: Window{425fa848 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  909): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/PMS     (  909): acquireWL(4260a618): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
,D/PMS     (  909): releaseWL(4260a618): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsRemoved
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/[PluginManager]RegisterService( 1332): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1332): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
W/AccTypeManager( 1358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
,I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
,I/IcingCorporaProvider( 2853): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4938 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1358): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  909): acquireWL(425d4e78): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(425d4e78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42588208): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2853): UpdateCorporaTask done [took 234 ms] updated apps [took 234 ms] 
,E/SQLiteDatabase( 4938): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4938): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4938): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4938): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4938): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4938): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4938): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4938): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4938): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4938): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4938): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4938): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4938): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4938): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4938): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4938): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4938): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4938): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4938): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4938): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4938): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4938): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4938): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4938): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4938): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4938): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4938): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4938): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4938): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4938): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4938): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4938): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4938): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4938): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4938): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4938): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4938): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4938): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4938): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4938): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4938): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4938): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4938): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4938): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4938): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4938): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4938): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4938): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4938): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4938): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4938): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4938): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4938): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4938): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4938): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4938): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4938): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4938): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4938): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4938): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4938): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4938): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4938): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4938): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4938): threadid=11: thread exiting with uncaught exception (group=0x416a1e30)
,E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4938): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4938): Process: com.google.android.apps.docs, PID: 4938
E/AndroidRuntime( 4938): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4938): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4938): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4938): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4938): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4938): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4938): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4938): 	at aho.run(AbstractDatabaseInstance.java:455)
,I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4956 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4938): killProcess, pid=4938
,D/Process ( 4938): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  909): Recipient 4938
,I/ActivityManager(  909): Process com.google.android.apps.docs (pid 4938) has died.
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4969 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4956): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4956): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4956): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4956): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4956): threadid=10: thread exiting with uncaught exception (group=0x416a1e30)
E/AndroidRuntime( 4956): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4956): Process: com.android.keychain, PID: 4956
E/AndroidRuntime( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4956): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4956): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4956): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  909): App crashed! Process: com.android.keychain
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
,D/AppTag  ( 4969): getInstance(Context context)
,D/AppTag  ( 4969): getInstance(Context context)
,D/AppTag  ( 4969): onCreate()
,I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  909): acquireWL(44185d28): PARTIAL_WAKE_LOCK  AsyncService 0x1 4151 10160 null
,D/PMS     (  909): releaseWL(44185d28): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  909): Resuming delayed broadcast
,E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452699561494.dbox_tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 4956): killProcess, pid=4956
,D/Process ( 4956): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,W/dalvikvm( 4178): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/Process (  909): killProcessQuiet, pid=4074
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4074:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  909): Recipient 4956
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.keychain (pid 4956) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/PackageBroadcastService( 2182): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2182): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2182): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2182): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2182): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2182): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b66d78 +
I/Prism.WidgetManager( 1274): onLoadItems() +
I/LocationSettingsChecker( 2182): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 2182): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 2182): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2182): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca8e020
,E/SQLiteDBG( 2182): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6ec78008
,W/dalvikvm( 2182): threadid=43: thread exiting with uncaught exception (group=0x416a1e30)
,E/DriveAsyncService( 2182): disk I/O error (code 3850)
E/DriveAsyncService( 2182): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2182): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2182): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2182): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2182): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2182): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2182): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2182): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2182): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2182): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2182): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2182): Process: com.google.android.gms, PID: 2182
E/AndroidRuntime( 2182): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2182): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2182): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2182): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2182): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2182): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2182): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2182): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2182): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2182): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2182): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2182): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2182): 	at java.lang.Thread.run(Thread.java:864)
,E/ActivityManager(  909): App crashed! Process: com.google.android.gms
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4074
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
E/SQLiteDatabase( 2182): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2182): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2182): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2182): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2182): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2182): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2182): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2182): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2182): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2182): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2182): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2182): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2182): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2182): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2182): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2182): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2182): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2182): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 2182): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2182): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2182): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2182): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2182): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2182): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2182): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2182): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2182): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2182): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2182): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2182): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Process ( 2182): killProcess, pid=2182
W/SQLiteOpenHelper( 2182): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2182): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2182): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/Process ( 2182): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/ActivityManager(  909): Recipient 2182
,I/ActivityManager(  909): Process com.google.android.gms (pid 2182) has died.
D/PMS     (  909): handleWLDeath(42588208): PARTIAL_WAKE_LOCK  Icing 0x1
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20997ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20997ms
,W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20996ms
,W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20996ms
,I/ActivityManager(  909): Resuming delayed broadcast
,W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20981ms
,W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20981ms
,E/SQLiteLog( 1342): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1342): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fe7b58
,W/dalvikvm( 1342): threadid=1: thread exiting with uncaught exception (group=0x416a1e30)
,E/AndroidRuntime( 1342): FATAL EXCEPTION: main
E/AndroidRuntime( 1342): Process: com.google.process.gapps, PID: 1342
E/AndroidRuntime( 1342): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1342): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1342): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1342): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1342): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1342): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1342): 	... 10 more
,E/ActivityManager(  909): App crashed! Process: com.google.process.gapps
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
,D/Process ( 1342): killProcess, pid=1342
,I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5002 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1342): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,W/PackageManager(  909): Unable to load service info ResolveInfo{423d0d28 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/DeviceManagement( 5002): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5002 dbg=false s=true
,I/DeviceManagement( 5002): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 5002): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 5002): WorkflowService: Starting workflow service
I/DeviceManagement( 5002): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b04ee0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5002): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5002): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 5002): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 5002): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  909): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5016 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 5002): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 5002): SessionStateController: Checking invariants...
,I/ActivityManager(  909): Recipient 1342
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Process com.google.process.gapps (pid 1342) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30809ms
,D/WifiService(  909): Client connection lost with reason: 4
,D/Documents( 5016): Loading roots for com.android.providers.downloads.documents
,D/Documents( 5016): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5016): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5016): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5016): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5016): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5016): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5016): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5016): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5016): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5016): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5016): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5016): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5016): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5016): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5016): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5016): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5016): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5016): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5016): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5016): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5016): 	at dalvik.system.NativeStart.main(Native Method)

```
