#### Test 50650278d0426ce_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  903): Waited long enough for: ServiceRecord{42d81530 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4331): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4331): ====startRecUseTime====
D/htc.customization.log.level( 4331):  is 
W/CustomizationLogLevel( 4331): Level value is invalid, use default level 2
D/CustomizationManager( 4331):  Read ACC file spent 0.050 (s)
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
D/CustomizationManager( 4331):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4331):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4331): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4331): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4331): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4331): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4331
D/PMS     (  903): acquireHCC(42cd9b78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(42cd5038): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1125054632
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41eb9970
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
D/PMS     (  903): acquireWL(42b81940): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4342 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1267): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4342): Binding Chromium to main looper Looper (main, tid 1) {41a77950}
I/LibraryLoader( 4342): Expected native library version number "",actual native library version number ""
I/chromium( 4342): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4342): Initializing chromium process, renderers=0
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f41668:true
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4342): 1101602872: getState(). Returning 12
D/PMS     (  903): acquireWL(41e78ef0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): acquireWL(41cc4188): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): releaseWL(41cc4188): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4342): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4342): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4342): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4342): Local Branch: 
I/Adreno-EGL( 4342): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4342): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4342):                  aa63bbd948f41d15fc72f585e
W/chromium( 4342): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/WIFI_ICON( 1113): WifiActivity: 0
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/dalvikvm( 4342): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4342): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4342): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4342): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4342): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4342): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4342): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4342): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4342): CordovaWebView is running on device made by: HTC
,W/AwContents( 4342): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  903): Disable input method client, pid=1267
,W/ResourceType( 4342): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4342): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ac36e8, mServedView=org.apache.cordova.engine.SystemWebView{41a89350 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  903): Enable input method client, pid=4342
,W/AwContents( 4342): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +282ms
,D/PMS     (  903): releaseWL(42b81940): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -43 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/JsMessageQueue( 4342): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4342): JniHelper::setJavaVM(0x41555048), pthread_self() = 1605817896
,D/JX-Cordova( 4342): jxcore cordova android initializing
,W/dalvikvm( 4342): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/SensorManager(  903): mEventCount = 1350
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 11.551MB for 95956-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 11.630MB for 143930-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 11.745MB for 215890-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 11.919MB for 323830-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 12.192MB for 485740-byte allocation
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/PluginManager( 4342): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 13.193MB for 1092904-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 14.058MB for 1639352-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 15.436MB for 2459024-byte allocation
,D/PMS     (  903): acquireWL(421d5298): PARTIAL_WAKE_LOCK  Icing 0x1 1220 10028 null
,D/PMS     (  903): releaseWL(421d5298): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(41d86a60): PARTIAL_WAKE_LOCK  Icing 0x1 1220 10028 null
,D/PMS     (  903): releaseWL(41d86a60): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(424b3a08): PARTIAL_WAKE_LOCK  Icing 0x1 1220 10028 null
,D/PMS     (  903): releaseWL(424b3a08): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 17.455MB for 3688532-byte allocation
,W/PluginManager( 4342): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 29ms. Plugin should use CordovaInterface.getThreadPool().
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
D/PMS     (  903): releaseHCC(42cd9b78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(42cd5038): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4342): Initializing JXcore engine
,W/jxcore-log( 4342): JXcore engine is ready
,W/jxcore-log( 4342): Starting JXcore engine
,W/jxcore-log( 4342): Platform android
W/jxcore-log( 4342): 
,W/jxcore-log( 4342): Process ARCH arm
W/jxcore-log( 4342): 
,I/jxcore-log( 4342): JXcore Cordova bridge is ready!
I/jxcore-log( 4342): 
,W/jxcore-log( 4342): JXcore engine is started
,I/chromium( 4342): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4342): Toggling radios to true
I/jxcore-log( 4342): 
,D/BluetoothAdapter( 4342): enable(): BT is already enabled..!
,D/WifiManager( 4342): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
,W/Settings:Agent(  903): Process.myPid(): 903,
W/Settings:Agent(  903): Process.myTid(): 1344
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: true pid=4342, uid=10348
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 2(ms)
D/WifiManager( 4342): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiManager( 4342): reconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  903): doBoolean: DISCONNECT
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): TDLS: Tear down peers
I/wpa_supplicant( 1164): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4342): Radios toggled
I/jxcore-log( 4342): 
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1164): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1164): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
,D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8b71bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1164): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1164): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA,_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  903):    returned true
D/WifiPerfLock(  903): release()
,D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
,D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
D/Tethering(  903): [isWifi] getHotspotEnabled: false
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  903): acquireWL(42474ae8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): Fast associate: Old scan results
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1164): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0(  903):    returned true
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19344 mDataStallAlarmIntent=PendingIntent{42508268: PendingIntentRecord{42464ec0 android broadcastIntent}}
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
,D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WISPrService( 3786): >>>>>WISPrService start isConnected = false<<<<<
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3786): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  903): New client listening to asynchronous messages
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
,D/PMS     (  903): acquireWL(4254ef40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
,D/libc    (  364): [NET] entry_id:5   entry:0xb76c5fd8  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb76c6310  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb76c6428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb76c6240  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb76c60e8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb76c64f0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 3786): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3786): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  903): releaseWL(41e78ef0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  903): acquireWL(423453b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1365/10028)
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  903):    returned false
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
D/BatSI   (  903): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  903): acquireWL(425dd410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  903): releaseWL(4254ef40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): releaseWL(425dd410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  903): releaseWL(423453b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4399 uid=10077 gids={50077}
,D/PMS     (  903): acquireWL(4377c3f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10077}
,V/AlarmManager(  903): sending alarm PendingIntent{422951e8: PendingIntentRecord{42304978 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449681174237, Int=60000
,D/PMS     (  903): releaseWL(4377c3f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4399): SMSBackupAgentService started
,D/SMSBackup( 4399): Checking restore status
,D/SMSBackup( 4399): Restore complete
,D/SMSBackup( 4399): cancelCheckAlarm
,D/SMSBackup( 4399): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  903): killProcessQuiet, pid=3602
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3602:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3602
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 3857): type=WIFI subType= reason=null isConnected=false
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3857/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1882/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4232/10100)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
D/PMS     (  903): acquireWL(431f1f18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1460/10028)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4232/10100)
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  903): NoActiveNetworkState
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2429/10021)
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4412 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ACRA    ( 4412): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4412): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4412): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4412): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4412): Preparing secondary program dexes.
V/DexLibLoader( 4412): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4412): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4412): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4412): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4412): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4412): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4412): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4412): Dex already copied
D/OdexVerifier( 4412): Odex verification is skipped.
,V/DexLibLoader( 4412): Creating class loader
,V/DexLibLoader( 4412): Finished creating class loader
V/DexLibLoader( 4412): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4412): Dex already copied
D/OdexVerifier( 4412): Odex verification is skipped.
,V/DexLibLoader( 4412): Creating class loader
,V/DexLibLoader( 4412): Finished creating class loader
V/DexLibLoader( 4412): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4412): Dex already copied
D/OdexVerifier( 4412): Odex verification is skipped.
V/DexLibLoader( 4412): Creating class loader
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,V/DexLibLoader( 4412): Finished creating class loader
V/DexLibLoader( 4412): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4412): Dex already copied
D/OdexVerifier( 4412): Odex verification is skipped.
,V/DexLibLoader( 4412): Creating class loader
,V/DexLibLoader( 4412): Finished creating class loader
,V/DexLibLoader( 4412): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4412): DexLibLoader.ensureDexLoaded took 20 ms
D/PMS     (  903): releaseWL(431f1f18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/dalvikvm( 4412): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4412): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4412): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4412): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4412): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4412): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4412): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4412): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-42
I/wpa_supplicant( 1164): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-43
I/wpa_supplicant( 1164): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1164): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1164): [NULL] 10:9a:dd:8e:22:d9 freq=2462 level=-91
D/wpa_supplicant( 1164): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1164): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1164): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1164): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1164): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1164): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1164): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1164): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1164): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1164):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1164):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-42
I/wpa_supplicant( 1164): Start print parameters
I/wpa_supplicant( 1164): wpa_s->wpa_state is 3
I/wpa_supplicant( 1164): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1164): isConcurrentMode() is 0
I/wpa_supplicant( 1164): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1164): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1164): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1164): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1164): wpa_s->reassociate is 1
I/wpa_supplicant( 1164): wpa_s->is_screen_on 1
I/wpa_supplicant( 1164): wpa_s->ifname wlan0
I/wpa_supplicant( 1164): End print parameters
I/wpa_supplicant( 1164): selected network = 1
D/wpa_supplicant( 1164): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  ,bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8b734e8  current_ssid=0x0
D/wpa_supplicant( 1164): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1164): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1164): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1164): check if in concurrent case
,I/wpa_supplicant( 1164): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1164): RSN: PMKSA cache search - network_ctx=0xb8b734e8 try_opportunistic=0
D/wpa_supplicant( 1164): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1164): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1164): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1164): nl80211: Unsubscribe mgmt frames handle 0xb8b72718 (mode change)
D/wpa_supplicant( 1164): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8b72718
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b72718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Connect (ifindex=22)
,D/wpa_supplicant( 1164):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164):   * freq=2412
D/wpa_supplicant( 1164):   * Auth Type 0
D/wpa_supplicant( 1164):   * WPA Versions 0x2
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1164): nl80211: Connect request send successfully
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=1 len=6
D/WirelessDisplayService(  903): getDiscoveryDongleList
,I/wpa_supplicant( 1164): reply (752) for get BSS: id=0
,I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-52
I/wpa_supplicant( 1164): tsf=0000000105701262
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=1
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-42
I/wpa_supplicant( 1164): tsf=0000000105701258
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=2
I/wpa_supplicant( 1164): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1164): freq=2427
I/wpa_supplicant( 1164): level=-82
I/wpa_supplicant( 1164): tsf=0000000105701267
I/wpa_supplicant( 1164): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1164): ssid=Gonzos
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=3
I/wpa_supplicant( 1164): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1164): freq=2437
I/wpa_supplicant( 1164): level=-82
I/wpa_supplicant( 1164): tsf=0000000105701271
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1164): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=4
I/wpa_supplicant( 1164): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-43
I/wpa_supplicant( 1164): tsf=0000000105701248
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1164): ssid=01ABC
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=5
I/wpa_supplicant( 1164): bssid=10:9a:dd:8e:22:d9
I/wpa_supplicant( 1164): freq=2462
I/wpa_supplicant( 1164): level=-91
I/wpa_supplicant( 1164): tsf=0000000105701274
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1164): ssid=Apple AirPort
I/wpa_supplicant( 1164): ####
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (6) end of scan result ==
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 5220, timestamp: 105701262, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -42, frequency: 2412, timestamp: 105701258, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 105701267, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -82, frequency: 2437, timestamp: 105701271, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -43, frequency: 2412, timestamp: 105701248, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 5: scan result = SSID: Apple AirPort, BSSID: 10:9a:dd:8e:22:d9, capabilities: [WPA2-PSK-CCMP][ESS], level: -91, frequency: 2462, timestamp: 105701274, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 6 to mScanResults
D/BatSI   (  903): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/dalvikvm( 4412): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Connect event
D/wpa_supplicant( 1164): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1164): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1164): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Add randomness: count=13 entropy=6
I/wpa_supplicant( 1164): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): TDLS: Remove peers on association
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1164): EAPOL: enable timer tick
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1164): getPrivFuncNum +	
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1164): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1164): Get randomness: len=32 entropy=7
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  903): Associated
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
,D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  903): BSSID was changed, update WiFi database
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8b729f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  903): updateConnectedAP...
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
E/FbInjectorInitializer( 4412): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6eebb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1164):    broadcast key
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1164): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1164): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1164): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1164): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1164): set send_ind_to_ndc = 0
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1164): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  903): updateConnectedAP...
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1164): EAPOL authentication completed successfully
I/wpa_supplicant( 1164): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  903): interfaceStatusChanged wlan0, true
,D/WifiStateMachine(  903): This record is existed, only update it...
D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  903): This record is existed, only update it...
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3786): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3786): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  903): Provision feature enable=false
,D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/DhcpStateMachine(  903): [StoppedState] Start DHCP
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -43 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 1
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
D/PMS     (  903): acquireWL(42c990a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42352988 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42352988 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4412): Verify
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4412): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4412): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,I/ActivityManager(  903): Killing 3221:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=3221
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PMS     (  903): acquireWL(436cfb08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1220 10028 null
I/ActivityManager(  903): Recipient 3221
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(43f019d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1220 10028 null
,D/PMS     (  903): releaseWL(436cfb08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,D/PMS     (  903): releaseWL(43f019d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4442 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): Util - no network available!
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,W/fb4a(:<default>):UserScope( 4412): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4412): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4412): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4442): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4442): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4442): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4442): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  903): killProcessQuiet, pid=3836
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4456 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Killing 3836:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4442/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4442/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4442/10078)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4412): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4473 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=4176
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4176:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4176
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,I/ActivityManager(  903): Recipient 3836
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 9.958MB for 84664-byte allocation
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4473): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4473): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 9.973MB for 28144-byte allocation
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4473): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/dalvikvm( 4412): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4412): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4412): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4412): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4412): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4412): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4412): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4412): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4412): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4412): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4412): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4412): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 4412): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4412): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4412): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4412): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4473): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/dalvikvm( 4412): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4412): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4473): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 10.041MB for 39954-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 10.117MB for 79892-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4473/10151)
,V/WebViewChromiumFactoryProvider( 4473): Binding Chromium to main looper Looper (main, tid 1) {41a81350}
,I/LibraryLoader( 4473): Expected native library version number "",actual native library version number ""
,I/chromium( 4473): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4473): Initializing chromium process, renderers=0
,D/PMS     (  903): acquireWL(436f23a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  903): acquireWL(437ac160): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4473): BLUETOOTH permission is missing!
D/PMS     (  903): releaseWL(436f23a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4473): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4473): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4473): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4473): Local Branch: 
I/Adreno-EGL( 4473): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4473): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4473):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4473): Starting up...
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4473/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4473/10151)
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,D/Process (  903): killProcessQuiet, pid=3968
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
I/ActivityManager(  903): Killing 3968:com.google.android.gm/u0a107 (adj 15): empty #17
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ba8988 u0 ReceiverList{43b762d8 4412 com.facebook.katana/10026/u0 remote:43b760c8}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ba8988 u0 ReceiverList{43b762d8 4412 com.facebook.katana/10026/u0 remote:43b760c8}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42351bd8 u0 ReceiverList{42351b78 4412 com.facebook.katana/10026/u0 remote:43f5f950}}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/PMS     (  903): acquireWL(430dbd78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1460 10028 null
,D/PMS     (  903): releaseWL(430dbd78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  903): Recipient 3968
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCoreFlp( 1460): Unknown pending intent to remove.
D/PMS     (  903): acquireWL(43e9e918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1460 10028 null
D/PMS     (  903): releaseWL(43e9e918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4412): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4412): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1164): EAPOL: startWhen --> 0,
,D/wpa_supplicant( 1164): EAPOL: disable timer tick
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42c990a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -42 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): gateway: /192.168.1.1
D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1164): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -42, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiP2pService(  903): InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19346 delay=15s
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  903): WAN detection
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
,D/WISPrService( 3786): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/MDST    (  903): default: setTeardownRequested(true)
D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@423a5d40
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
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
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  903): acquireWL(43f1f448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4442/10078),
,I/QuickSettingWifi( 1113): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  903): acquireWL(43ed7540): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1220 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  903): acquireWL(43fbb6c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1220 10028 null
D/PMS     (  903): releaseWL(43ed7540): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/CheckinService( 1220): Preparing to send checkin request
,I/EventLogService( 1220): Accumulating logs since 1449681124346
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1220): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1220): Using GMS GoogleHttpClient
D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  903): releaseWL(43f1f448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1220/10028)
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1220/10028)
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1220): awaiting user notification for token
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41d44b48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 0 7 2 12
,I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4548 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4548): install
,I/MultiDex( 4548): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4548): loading existing secondary dex files
,I/MultiDex( 4548): load found 1 secondary dex files
,I/MultiDex( 4548): install done
,I/ProviderInstaller( 4548): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4548): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4548): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4548): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4548): Local Branch: 
I/Adreno-EGL( 4548): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4548): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4548):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  903): releaseWL(42474ae8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/CaptivePortalTracker(  903): NoActiveNetworkState
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
D/PMS     (  903): acquireWL(43f0ce58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4442/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3879/10051)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1460/10028)
D/PMS     (  903): acquireWL(43b32e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1882/1000)
V/Tethering(  903): bSetPropertyMultiRAB:false
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/NetworkMonitor( 3857): type=WIFI subType= reason=null isConnected=true
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/acms    ( 1882): Checking Certificates
I/acms    ( 1882): Checking Developer Certificates
I/acms    ( 1882): Checking Application Certificates
I/acms    ( 1882): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1882): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1882): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1882): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1882): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1882): Updating next query delay: 75600000
I/mlserverapp( 1882): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1882): cancelACMSProgrammedChecks
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3857/10154)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4232/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/PMS     (  903): releaseWL(43b32e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4232/10100)
D/PMS     (  903): releaseWL(43f0ce58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2429/10021)
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(42cee970): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1220 10028 null
D/PMS     (  903): releaseWL(42cee970): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,I/Adreno-EGL( 4548): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4548): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4548): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4548): Local Branch: 
I/Adreno-EGL( 4548): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4548): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4548):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1365): [NET] getaddrinfo-, 1
,D/libc    ( 1365): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c189 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  903): acquireWL(424bced0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1365 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -43 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  903): BroadcastRSSIForIMS, newrssi =-43 , oldRssi= -200
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/MobileConnectivityChangeReceiver( 4442): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4442): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1396): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1396): service - onStartCommand() REMOVE current location bundle
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED 3 -> 3
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/AutoSetting( 1396): service - handleMessage() setting current location null
,I/Adreno-EGL( 4548): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4548): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4548): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4548): Local Branch: 
I/Adreno-EGL( 4548): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4548): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4548):                  aa63bbd948f41d15fc72f585e
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1396): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4473/10151)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 211
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1365): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
,I/dalvikvm-heap( 4114): Grow heap (frag case) to 13.519MB for 1821008-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,W/fb4a(:<default>):UserScope( 4412): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4412): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [5][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,W/Settings( 4548): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  903): acquireWL(422a8c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  903): releaseWL(422a8c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4548/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/GCM     ( 1365): Connected
,I/CheckinTask( 1220): Sending checkin request (9010 bytes)
D/PMS     (  903): acquireWL(423f6a00): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  903): releaseWL(424bced0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/libc    ( 1220): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
,D/libc    ( 1220): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f5a0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  903): releaseWL(423f6a00): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): acquireWL(422f5788): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
E/fb4a(:<default>):LocalFbBroadcastManager( 4412): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1365): Message class mpf
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  903): releaseWL(422f5788): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(424d54b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  903): releaseWL(424d54b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/libc    ( 1220): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/PMS     (  903): releaseWL(437ac160): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  903): acquireWL(42c47840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=109648, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=38 [18][7][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,D/PMS     (  903): releaseWL(42c47840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/ClockThread( 1113): now=1449681180061 next=59939
,D/PMS     (  903): acquireWL(4317b200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  903): releaseWL(4317b200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1220/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1220/10028)
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1220): awaiting user notification for token
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41d49fc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 0 6 2 12
,I/CheckinTask( 1220): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1220): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): releaseWL(43fbb6c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1220): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c6fdf0 that was originally bound here
E/ActivityThread( 1220): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c6fdf0 that was originally bound here
E/ActivityThread( 1220): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1220): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1220): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1220): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1220): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1220): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1220): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1220): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1220): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1220): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1220): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1220): 	at bks.a(SourceFile:298)
E/ActivityThread( 1220): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1220): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1220): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1220): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1365): GCM config loaded
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4209dba8
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4209dba8, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422ddee0
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@4254b168
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  903): Couldn't get kernel wake lock stats
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
,D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  903): mWirelessDisplayManager is null
,I/SensorManager(  903): mEventCount = 1500
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 368ms
D/NfcService( 1253): ScreenObserver: OFF
D/NfcService( 1253): applyRouting - 0
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  903): Disable input method client, pid=4342
,D/NfcService( 1253): applyRouting -2
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43eca0e8)
D/PMS     (  903): acquireWL(43f907e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  903): releaseWL(43f907e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/PMN     (  903): wakingUp
I/WindowManager(  903): No lock screen! windowToken=null
D/PMN     (  903): onScreenOn
,D/PMS     (  903): acquireWL(4325a350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  903): releaseWL(4325a350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NfcService( 1253): applyRouting - 0
,D/MtpService( 2429): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2429): [MTP][onReceive]-
D/NfcService( 1253): applyRouting -2
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): acquireWL(425568c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
,D/PMS     (  903): releaseWL(425568c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1396): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3786): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3786): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3786): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3786): Cust_ConnectToPC   : spcsc>false
D/        ( 3786): Cust_ConnectToPC   : IPT>true
D/        ( 3786): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3786): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3786): hasRemovableStorageSlot: true
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
D/SmartNS_Utility( 3786): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19347 delay=15s
,D/SmartNS_NSReceiver( 3786): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3786): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): SET_SCREEN_ON:On
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1164): getPrivFuncNum +	
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3786): onReceive:android.intent.action.USER_PRESENT
,I/ClockThread( 1113): stop update clock
W/Settings( 3786): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3786):  defaultType:0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -43 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/NetworkPolicy(  903): updateScreenOn: false
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4590 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED 3 -> 3
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b6ff +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/23.59.123.86
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): onScreenOn: 1449681181210
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1779): onScreenOn: 1449681181210
D/PMS     (  903): acquireWL(43369ce8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1460 10028 null
D/PMS     (  903): releaseWL(43369ce8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422ddee0
,W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  903): pid=903, uid=1000
,W/ContextImpl( 4590): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422ddee0, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@4254b168
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(43f5eed8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,D/PMS     (  903): acquireWL(43ba2800): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4590 1000 null
D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19347 mDataStallAlarmIntent=PendingIntent{4349ac10: PendingIntentRecord{42464ec0 android broadcastIntent}}
,D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): SET_SCREEN_ON:Off
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1164): getPrivFuncNum +	
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1164): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1164): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4590): isEpsOn(), nState = 0
I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
,D/PMS     (  903): acquireWL(434dd740): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  903): updateScreenOn: false
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(43ba2800): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  903): releaseWL(434dd740): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/SmartSyncUtils( 4590): getMobilePolicyEnabled, result = true
,D/Process (  903): killProcessQuiet, pid=4202
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Killing 4202:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4202
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
W/ContextImpl( 4590): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4590): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4590): getMobilePolicyEnabled, result = true
,D/ContactMessageStore( 1237): start background delete task...
,D/SmartSyncUtils( 4590): isEpsOn(), nState = 0
D/ContactMessageStore( 1237): size: 0 , 0
,D/ContactMessageStore( 1237): Background delete complete
D/WifiService(  903): New client listening to asynchronous messages
,D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4254b168
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,D/DotMatrix( 1568): [EventService] getTotalRam: 1873 Mb
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4254b168, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4254b168, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4254b168
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1779): onScreenOff
D/PMS     (  903): acquireWL(438d4990): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1460 10028 null
D/PMS     (  903): releaseWL(438d4990): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4254b6b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4254b6b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  903): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  903): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  903): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  903): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  903): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  903): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  903): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  903): Activity pause timeout for ActivityRecord{4202f028 u0 com.test.thalitest/.MainActivity t2}
,I/GAV2    ( 4473): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  903): acquireWL(43fd4868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1460 10028 null
,D/PMS     (  903): acquireWL(42cc0b28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1460 10028 null
,D/PMS     (  903): releaseWL(43fd4868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(42cc0b28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/jxcore-log( 4342): Test app app.js loaded
I/jxcore-log( 4342): 
,I/Choreographer( 4342): Skipped 519 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4342): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4342): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a89350 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  903): releaseWL(43f5eed8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4342): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/AutoSetting( 1480): service - handleMessage() stop self
,D/Process (  903): killProcessQuiet, pid=4232
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 4232:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/AutoSetting( 1480): service - onDestroy() END
D/AutoSetting( 1480): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4255
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4255:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4255
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4232
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 10.981MB for 41560-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 11.014MB for 62336-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 11.014MB for 42970-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 11.055MB for 65476-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 11.062MB for 44210-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 11.094MB for 57344-byte allocation
,D/libc    ( 4412): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4412): [NET] getaddrinfo-,err=8
D/libc    ( 4412): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4412): [NET] getaddrinfo-, 1
,D/libc    ( 4412): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ca48 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11
D/libc    (  364): [NET]res_nsend:resplen=93
D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4412): [NET] getaddrinfo_proxy-, success
I/global  ( 4412): call createSocket() return a new socket.
D/libc    ( 4412): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
,D/libc    ( 4412): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4412): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4412): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(430c9ca8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4412 10026 null
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4412): I/O error closing connection
I/global  ( 4412): java.net.SocketException: Socket is closed
I/global  ( 4412): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4412): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4412): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4412): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4412): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4412): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4412): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4412): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4412): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4412): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4412): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4412): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4412): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4412): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4412): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4412): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4412): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4412): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4412): Removing a connection that never existed!
D/PMS     (  903): releaseWL(430c9ca8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(43484cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43484cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1396): service - mHandler: update timezone
,D/AutoSetting( 1480): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1480): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1480): service - onCreate()
,D/AutoSetting( 1480): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1480): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1480): service - mHandler: update timezone
,D/AutoSetting( 1480): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1480): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
,D/DotMatrix( 1568): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1480): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1480): service - processTimeZoneID() system nitz is valid: false (false)
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1480): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1480): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41ad7c00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 2 6 3 11
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(42b7b178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{4221ba00: PendingIntentRecord{42448008 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140893, Int=0
D/PMS     (  903): acquireWL(43091a68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
V/AlarmManager(  903): sending alarm PendingIntent{433f0488: PendingIntentRecord{42451258 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141009, Int=0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  903): releaseWL(42b7b178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  903): acquireWL(42d80d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cd50 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  903): releaseWL(42d80d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1396): service - handleMessage() stop self
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/AutoSetting( 1396): service - onDestroy() END
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success,
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): releaseWL(43091a68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  903): killProcessQuiet, pid=3879
,I/ActivityManager(  903): Killing 3879:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 3879
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43323878 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1480): service - handleMessage() stop self
,D/AutoSetting( 1480): service - onDestroy() END
,D/AutoSetting( 1480): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4273
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4273:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4273
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(43575db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=169649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43575db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43e6fc30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(43e6fc30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1237): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(435ae120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(435ae120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43f99058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{420f9398: PendingIntentRecord{42a91f48 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226702, Int=0
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4631 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  903): sending alarm PendingIntent{423e58a8: PendingIntentRecord{420d5500 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449681290819, Int=10800000
,D/PMS     (  903): releaseWL(43f99058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4631/10047)
,D/Process (  903): killProcessQuiet, pid=4289
I/ActivityManager(  903): Killing 4289:com.htc.calendar/u0a13 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 4289
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,D/PMS     (  903): acquireWL(444fee10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=229648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(444fee10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(444d2770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): acquireWL(44497510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{42d6e730: PendingIntentRecord{42a91f48 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230899, Int=0
,D/PMS     (  903): releaseWL(444d2770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
D/PMS     (  903): releaseWL(44497510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43bc37e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43bc37e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(437293f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=289648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(437293f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43728420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43728420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(4350caf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4350caf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(43478638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=349648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43478638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(434358f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(434358f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1365): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1365): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1365): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1365): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1365): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,E/PlayEventLogger( 4078): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4078): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4078): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4078): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4078): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4078): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4078): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4078): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41c29d60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 4 13 4 12
,D/libc    ( 4078): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4078): [NET] getaddrinfo-,err=8
D/libc    ( 4078): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4078): [NET] getaddrinfo-, 1
,D/libc    ( 4078): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =366f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 20
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4078): [NET] getaddrinfo_proxy-, success
I/global  ( 4078): call createSocket() return a new socket.
D/libc    ( 4078): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4078): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4078): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4078): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(4257de98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4257de98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(41f9b748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=409649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(41f9b748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42461f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{43fae428: PendingIntentRecord{43be7920 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=410622, Int=300000
,V/AlarmManager(  903): sending alarm PendingIntent{4351e000: PendingIntentRecord{4257da20 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449681420156, Int=1800000
,V/AlarmManager(  903): sending alarm PendingIntent{42c5ea68: PendingIntentRecord{437ac288 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1449681427429, Int=0
,D/PMS     (  903): acquireWL(42352fe0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1220 10028 null
,D/PMS     (  903): acquireWL(422b4088): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1220 10028 null
,D/PMS     (  903): releaseWL(42352fe0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1220): Aggregate from 1449681178149 (log), 1449679620109 (data)
,D/PMS     (  903): releaseWL(42461f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  903): releaseWL(422b4088): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/Uploader( 1220): No account for auth token provided
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
,D/libc    ( 1220): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9f8 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1220): [NET] getaddrinfo_proxy-, success
I/global  ( 1220): call createSocket() return a new socket.,
D/libc    ( 1220): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,D/PMS     (  903): acquireWL(423bbae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(423bbae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42307ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(42307ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4342): Toggling radios to false
I/jxcore-log( 4342): 
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  903): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42417160 mBinding = false
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1343
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 2(ms)
,D/BluetoothManagerService(  903): Message: MESSAGE_DISABLE
D/BluetoothManagerService(  903): Sending off request.
,D/WifiManager( 4342): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
D/BluetoothAdapterState( 1604): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1604): Setting state to 13
I/BluetoothAdapterState( 1604): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1604): Broadcasting updateAdapterState() to 1 receivers.
D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothManagerService(  903): +onBluetoothStateChange prev=12 new=13
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1447
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
D/WifiService(  903): setWifiEnabled: false pid=4342, uid=10348
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false,
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/BluetoothAdapterProperties( 1604): onBluetoothDisable()
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
I/BluetoothAdapterState( 1604): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 1604): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 1604): BTM_SetDiscoverability
I/bt-btm  ( 1604): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1604): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1604): br_edr_supported=0x0
I/bt-btm  ( 1604): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1604): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1604): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1604): btm_ble_update_adv_flag old=0x0
I/BluetoothAdapterProperties( 1604): adapterPropertyChangedCallback with type:7 len:4
,I/bt-btm  ( 1604): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1604): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1604): BTM_SetConnectability
I/bt-btm  ( 1604): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1604): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1604): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 4(ms)
D/BluetoothAdapterProperties( 1604): Scan Mode:20
E/BTIF_CORE( 1604): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1604): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  903): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterState( 1604): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1604): BTA_JvDeleteRecord
I/bt-btif ( 1604): BTA_JvRfcommStopServer
D/bt-btm  ( 1604): BTM_FreeSCN 
,I/bt-btif ( 1604): BTA_JvDeleteRecord
I/bt-btif ( 1604): BTA_JvRfcommStopServer
D/bt-btm  ( 1604): BTM_FreeSCN 
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 1604): bta_jv_rfcomm_stop_server
I/bt-btif ( 1604): bta_jv_rfcomm_stop_server
I/bt-btif ( 1604): BTA_JvRfcommStopServer
I/bt-btm  ( 1604): BTM_FreeSCN 
D/bt-btm  ( 1604): BTM_FreeSCN 
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1604): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1604): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1604): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1604): BTM_SEC_CLR[15]: id 54
I/bt-btif ( 1604): BTA_JvDeleteRecord
,I/bt-btif ( 1604): BTA_JvRfcommStopServer
D/bt-btm  ( 1604): BTM_FreeSCN 
I/bt-btif ( 1604): BTA_JvDeleteRecord
I/bt-btif ( 1604): BTA_JvRfcommStopServer
D/bt-btm  ( 1604): BTM_FreeSCN 
I/bt-btif ( 1604): BTA_JvDeleteRecord
I/bt-btif ( 1604): BTA_JvRfcommStopServer
D/bt-btm  ( 1604): BTM_FreeSCN 
V/BluetoothSapService( 1604): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 1604): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:12
,D/PMS     (  903): acquireWL(42596160): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1604 1002 null
E/bt-btif ( 1604): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1604): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1604): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1604): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1604): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1604): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1604): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1604): Write Extended Inquiry Response to controller
I/bt-btm  ( 1604): Write Extended Inquiry Response to controller
I/bt-btm  ( 1604): Write Extended Inquiry Response to controller
I/bt-btm  ( 1604): Write Extended Inquiry Response to controller
I/bt-btm  ( 1604): BTM_SetDiscoverability
I/bt-btm  ( 1604): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1604): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1604): br_edr_supported=0x0
I/bt-btm  ( 1604): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1604): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1604): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1604): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1604): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1604): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1604): BTM_SetConnectability
I/bt-btm  ( 1604): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1604): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1604): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1604): BTM_IsInquiryActive
I/bt-btm  ( 1604): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1604): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1604): BTM_FreeSCN 
I/bt-btm  ( 1604): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1604): BTM_FreeSCN 
I/bt-btm  ( 1604): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1604): AVRC_Close handle:0
I/IntentController( 1113): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1604): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1604): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1604): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1604): GATT_Deregister gatt_if=3
I/bt-att  ( 1604): GATT_Deregister gatt_if=4
D/BluetoothRemoteDevices( 1604): Wake lock Aquired
V/BluetoothPbapReceiver( 1604): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1604): ***********state = 13
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1779): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41aa4120
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1779): onDeInitialized
D/BluetoothMasReceiver( 1604): Bluetooth STATE CHANGED to 13
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1779): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1779): getNotificationManager
V/BluetoothSapReceiver( 1604): SapReceiver onReceive 
V/BluetoothSapReceiver( 1604): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1604):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 1604): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 1604): Pbap Service closeService in
D/PMS     (  903): acquireWL(42351438): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3786 1000 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1779): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1779):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1779): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1779): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1779): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1779):  + mTag.getPrimaryDeviceList() = []
,D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1779): deinit: 0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1779): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1779): shutdownStateMachine
D/BluetoothManagerService(  903): Message: MESSAGE_UNREGISTER_ADAPTER
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1779): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1779): setPendingRequestAlarm: false, mContext = null, null
D/BluetoothManagerService(  903): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423fcf18:true
V/BluetoothPbapService( 1604): successfully stopped pbap service
V/BluetoothPbapService( 1604): Pbap Service closeService out
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1779): Exit IdleState
I/BtOppRfcommListener( 1604): stopping Accept Thread
,I/BtOppRfcommListener( 1604): BluetoothSocket listen thread finished
W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/WirelessDisplayService(  903): getMirrorDisplayStatus:falsecurState:1
,D/WifiPerfLock(  903): release()
I/jxcore-log( 4342): Radios toggled
I/jxcore-log( 4342): 
D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
V/BluetoothSapService( 1604): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1604): state: 13
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  903): releaseWL(42351438): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  903): acquireWL(42376698): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/BluetoothAdapter( 1604): 1101650544: getState(). Returning 13
V/BluetoothSapService( 1604): Stopping SAP server process
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/PMS     (  903): acquireWL(42c990a0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3786 1000 null
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425cb6d8:true
D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
I/QuickSettingBluetooth( 1113): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PhoneStatusBar( 1113): removeIcon slot=bluetooth index=12 viewIndex=0
I/LocationAgent( 3786): new LocationAgent instance!!
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
,D/HtcTagManager( 3786): HtcTagManager construction complete
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19348 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  903):    returned null
,E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  903): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4669 uid=10037 gids={50037, 3002, 3001}
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
,D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  903):    returned null
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
V/BluetoothSapService( 1604): Sap Service closeSapService in
V/BluetoothSapService( 1604): Close listen Socket : 
V/BluetoothSapService( 1604): Close rfcomm Socket : 
V/BluetoothSapService( 1604): Close sapd  Socket : 
V/BluetoothSapReceiver( 1604): BluetoothSapReceiver deinit
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiP2pService(  903): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
,D/BluetoothAdapter( 3786): 1103278720: getState(). Returning 13
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
D/BluetoothInputDevice( 3786): BluetoothInputDevice()
V/BluetoothSapService( 1604): successfully stopped Sap service
,V/BluetoothSapService( 1604): Sap Service closeSapService out
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
V/BluetoothPbapService( 1604): Pbap Service onDestroy
V/BluetoothPbapService( 1604): Pbap Service closeService in
,V/BluetoothPbapService( 1604): Pbap Service closeService out
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiP2pService(  903): P2pDisablingState
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiDisplayController(  903): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  903): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  903): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  903): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  903): set wifi.miracastlock to 0 for disconnect case
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '51 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 51 Failed to remove route from default table (No such process)'
D/WifiP2pService(  903): P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): p2p socket connection lost
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiStateMachine(  903): Call handleNetworkDisconnect() in SupplicantStoppingState
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3786): 1103278720: getState(). Returning 13
D/BluetoothManagerService(  903): Registered receivers: 7
,D/BluetoothInputDevice( 3786): BluetoothInputDevice(): Fake return onServiceConnected
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/HidProfile( 3786): Bluetooth service connected
,W/BluetoothInputDevice( 3786): Proxy not attached to service
D/BluetoothPan( 3786): BluetoothPan()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
V/BluetoothSapService( 1604): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41ad60c0
V/BluetoothSapService( 1604): Sap Service closeSapService in
V/BluetoothSapService( 1604): Close listen Socket : 
V/BluetoothSapService( 1604): Close rfcomm Socket : 
V/BluetoothSapService( 1604): Close sapd  Socket : 
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
V/AudioService(  903): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  903):     Client/Owner: Client
V/AudioService(  903):     GroupId: 
V/AudioService(  903):     Passphrase: 
V/AudioService(  903):     SessionId: 0
V/AudioService(  903):     IP Address: }
D/HtcEffectManagerBase(  903): onEventChanged id=5 status=false
D/HtcEffectManager(  903): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  903): convertEffect before=902
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,D/HtcEffectManager(  903): convertEffect after=902
V/BluetoothSapService( 1604): Sap Service closeSapService out
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
V/BluetoothSapService( 1604): ***onDestroyed***
D/WifiP2pService(  903): P2pDisabledState
D/WifiP2pService(  903): P2pDisabledState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  903):  WFD CtrlPort: 0
D/WifiP2pService(  903):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  903):  WFD CtrlPort: 0
D/WifiP2pService(  903):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  903): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
I/WifiDisplayController(  903): updateConnection
I/WifiDisplayController(  903): mConnectingDevice = null,  mDesiredDevice = null
,I/WifiDisplayController(  903): updateConnection enter step 4
D/WifiDisplayController(  903): Failed to set WFD info with reason 2.
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/WifiP2pService(  903): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  903): Registered receivers: 8
D/WifiNative-wlan0(  903):    returned true
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/BluetoothAdapter( 3786): 1103278720: getState(). Returning 13
D/BluetoothPan( 3786): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 3786): Bluetooth service connected
,D/BluetoothMap( 3786): Create BluetoothMap proxy object
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 9
,E/BluetoothMap( 3786): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '52 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 52 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
,D/PMS     (  903): acquireWL(42540ae8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/BluetoothManagerService(  903): Registered receivers: 10
D/libc    (  364): [NET] entry_id:4   entry:0xb76c5d90  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb76c6410  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb76c6830  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb76c6108  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb76c5ea0  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb76c6020  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/BluetoothSap( 3786): BluetoothSap() call bindService
D/WifiNative-p2p0(  903): doBoolean: TERMINATE
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/PMS     (  903): acquireWL(436cfc80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  903): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 1164): Supplicant Terminat @ wpa_supplicant_deinit function
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-p2p0(  903):    returned true
D/wpa_supplicant( 1164): TDLS: Tear down peers
I/wpa_supplicant( 1164): wpa_driver_nl80211_disconnect(reason_code=3)
,D/HtcBtWidget_BTWidgetProvider( 4669): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4669): updateWidget(context) for widget: 
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  903): releaseWL(436cfc80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/BluetoothPbap( 3786): BluetoothPbap()
D/BluetoothManagerService(  903): registerStateChangeCallback+
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 11
D/BluetoothAdapter( 3786): 1103278720: getState(). Returning 13
D/BluetoothPbap( 3786): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3786): Bluetooth service connected
,D/LocalBluetoothProfileManager( 3786): LocalBluetoothProfileManager construction complete
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/PMS     (  903): acquireWL(423c5090): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1164): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1164): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164): TDLS: Remove peers on disassociation
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/IntentController( 1113): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4442/10078)
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
I//system/bin/ip(  364): RTNETLINK answers: No such process
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8b71bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1164): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1164): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstat,e: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WIFI_ICON( 1113): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/DockEventReceiver( 3786): finishStartingService: stopping service
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WISPrService( 3786): >>>>>WISPrService start isConnected = false<<<<<
I/ActivityManager(  903): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4686 uid=10048 gids={50048}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1365/10028)
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
D/WISPrService( 3786): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=-2ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 3786): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 3786): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
E/BluetoothFtpService:RfcommSocketAcceptThread( 1604): Shutdown
D/PMS     (  903): releaseWL(42c990a0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothMasReceiver( 1604): Bluetooth STATE CHANGED to 13
D/PMS     (  903): releaseWL(42540ae8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
W/bt-btif ( 1604): ag scb idx 1 not allocated
W/bt-btif ( 1604): ag scb idx 2 not allocated
E/bt-btif ( 1604): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1604): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1604): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1604): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1604): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1604): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1604): L2CAP - PSM: 0x0017 not found for deregistration
D/Process (  903): killProcessQuiet, pid=4305
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  903): releaseWL(423c5090): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/ActivityManager(  903): Killing 4305:com.android.settings:remote/1000 (adj 15): empty #17
I/QuickSettingWifi( 1113): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1779): Received state change = 13
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1779): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41aa4120
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): deinitLeServices: null
I/ActivityManager(  903): Recipient 4305
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/bt_userial_mct( 1604): userial_close userial_thread_created userial_running is 1 
I/ActivityManager(  903): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4703 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  903): killProcessQuiet, pid=4219
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4219:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/HtcWiFiWidget_WiFiWidgetProvider( 4686): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4686): updateWidget(context) for widget: 
,D/Process (  903): killProcessQuiet, pid=4078
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  903): Recipient 4219
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Killing 4078:com.android.vending/u0a73 (adj 15): empty #17
,V/Settings:HtcSettingsApplication( 4703): [4703/4703] onCreate()
,D/WifiService(  903): New client listening to asynchronous messages
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4078
,D/Process (  903): killProcessQuiet, pid=4399
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4399:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,E/wpa_supplicant( 1164): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1164): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
,I/wpa_supplicant( 1164): nl80211: wpa_driver_nl80211_deinit
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4399
,D/wpa_supplicant( 1164): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1164): nl80211: Unsubscribe mgmt frames handle 0xb8b72718 (mode change)
I/wpa_supplicant( 1164): htc_wext_command_deinit +
I/wpa_supplicant( 1164): htc_wext_command_deinit -
E/wpa_supplicant( 1164): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1164): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1164): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1164): TDLS: Tear down peers
I/wpa_supplicant( 1164): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,I/bt-btif ( 1604): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1604): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1604): Received stop request...Stopping profile...
,D/BluetoothHeadset( 1237): Proxy object disconnected
D/BluetoothPhoneService( 1237): BluetoothHeadset onServiceDisconnected
,D/BluetoothHeadset(  903): Proxy object disconnected
D/BluetoothHeadset( 1237): Proxy object disconnected
D/BluetoothHeadset( 1113): Proxy object disconnected
,I/QuickSettingMiniLite( 1113): btListener.disconnect:HEADSET
D/A2dpService( 1604): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1604): doQuit
D/A2dpStateMachine( 1604): Exit Disconnected: -1
,D/BluetoothAdapterState( 1604): Stopping profile services that were post enabled
,D/BluetoothA2dp(  903): Proxy object disconnected
,D/HidService( 1604): Received stop request...Stopping profile...
,D/HealthService( 1604): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1604): Profile still running: com.android.bluetooth.hdp.HealthService
,D/PanService( 1604): Received stop request...Stopping profile...
D/PanService( 1604): stop
,D/PanService( 1604): stop: mTetherAc send disconnect
,D/BluetoothTethering(  903): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  903): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  903): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  903): BluetoothPAN Proxy object disconnected
,W/BluetoothHeadsetServiceJni( 1604): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1604): Cleaning up Bluetooth Handsfree callback object
,D/BtGatt.DebugUtils( 1604): handleDebugAction() action=null
D/BtGatt.GattService( 1604): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1604): stop()
D/BluetoothAdapterService( 1604): Profile still running: com.android.bluetooth.hdp.HealthService
,D/A2dpStateMachine( 1604): cleanup
D/Avrcp   ( 1604): Unregistering previous receiver
D/BluetoothAdapterService( 1604): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1604): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1604): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1604): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1604): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1604): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1604): Cleaning up Bluetooth Health object
D/PanService( 1604): CMD_CHANNEL_DISCONNECTED
D/PanService( 1604): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 1604): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1604): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1604): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1604): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1604): Setting state to 10
I/BluetoothAdapterState( 1604): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1604): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  903): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  903): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 1604): Entering OffState
,D/BluetoothHeadset( 1237): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3786): onBluetoothStateChange: up=false
,E/BluetoothInputDevice( 3786): 
E/BluetoothInputDevice( 3786): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41c37258
E/BluetoothInputDevice( 3786): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3786): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3786): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3786): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3786): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3786): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3786): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothMap( 3786): onBluetoothStateChange: up=false
,E/BluetoothMap( 3786): 
E/BluetoothMap( 3786): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41c39b60
E/BluetoothMap( 3786): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3786): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3786): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3786): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3786): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3786): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3786): 	at dalvik.system.NativeStart.run(Native Method)
E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
D/BluetoothHeadset(  903): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1113): onBluetoothStateChange: up=false
W/WifiHW  (  903): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
,I/wpa_ctrl(  903): [wpa_ctrl_close] ctrl=0x5cb56280
I/wpa_ctrl(  903): [wpa_ctrl_close] ctrl=0x62e91298
W/WifiHW  (  903): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
,E/BluetoothPan( 3786): 
E/BluetoothPan( 3786): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41c387e0
E/BluetoothPan( 3786): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3786): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3786): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3786): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3786): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3786): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3786): 	at dalvik.system.NativeStart.run(Native Method)
D/WifiStateMachine(  903): setAuthErrorNotificationVisible visible=false
D/WifiNative-wlan0(  903): doBoolean: SET_WIFI_ON 0
D/BluetoothPbap( 3786): onBluetoothStateChange: up=false
,D/WifiNative-wlan0(  903):    returned false
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
,E/BluetoothPbap( 3786): 
E/BluetoothPbap( 3786): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41c3fec0
E/BluetoothPbap( 3786): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3786): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3786): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3786): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3786): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3786): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3786): 	at dalvik.system.NativeStart.run(Native Method)
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothHeadset( 1237): onBluetoothStateChange: up=false
I/IntentController( 1113): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  903): WIFI Trun OFF
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WIFI_ICON( 1113): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothA2dp(  903): onBluetoothStateChange: up=false
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
D/HtcWiFiWidget_WiFiWidgetProvider( 4686): onWiFiStateChanged() for widget: 
E/WifiStateMachine(  903): [MLHD] Error! unhandled message 6 { when=-123ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/HtcWiFiWidget_WiFiWidgetProvider( 4686): updateWidget(context) for widget: 
D/PMS     (  903): acquireWL(435f3c00): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/BluetoothSap( 3786): onBluetoothStateChange on: false
,D/BluetoothManagerService(  903): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  903): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1822): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bc0fb0
D/BluetoothAdapter( 1822): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1237): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d1a9b0
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothAdapter( 1237): onBluetoothServiceDown: done
W/BluetoothHeadset( 1113): Proxy not attached to service
I/QuickSettingMiniLite( 1113): updateLiteState:no connect device!
D/BluetoothAdapter( 1460): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bda308
D/BluetoothAdapter( 1460): onBluetoothServiceDown: done
D/BluetoothAdapter( 1604): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41a9bee0
D/BluetoothDevice( 1604): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1604): onBluetoothServiceDown: done
D/BluetoothAdapter(  903): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42417160
D/BluetoothAdapter(  903): onBluetoothServiceDown: done
D/BluetoothAdapter( 1113): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41e764a8
D/BluetoothAdapter( 1113): onBluetoothServiceDown: done
D/BluetoothAdapter( 1253): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b55b00
D/BluetoothAdapter( 1253): onBluetoothServiceDown: done
D/BluetoothAdapter( 3786): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c2bce8
D/BluetoothAdapter( 3786): onBluetoothServiceDown: done
D/BluetoothAdapter( 1779): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41aa49f0
D/BluetoothAdapter( 1779): onBluetoothServiceDown: done
D/BluetoothAdapter( 4342): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41a92aa0
D/BluetoothAdapter( 4342): onBluetoothServiceDown: done
,D/BluetoothManagerService(  903): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42417160 mBinding = false
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
D/BluetoothManagerService(  903): Sending unbind request.
D/WISPrService( 3786): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3786): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothAdapterService( 1604): Cleaning up adapter native....
,I/bt-btif ( 1604): HAL bt_hal_cbacks->thread_evt_cb
D/BluetoothAdapterService( 1604): Done cleaning up adapter native....
,D/BluetoothAdapterService(1101632368)( 1604): ****onDestroy()********
,D/PMS     (  903): releaseWL(42596160): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/BtGatt.GattService( 1604): cleanup()
W/bt-btif ( 1604): GATTC Module not enabled/already disabled
W/bt-btif ( 1604): GATTS Module not enabled/already disabled
D/BluetoothManagerService(  903): Bluetooth State Change Intent: 13 -> 10
D/NfcHandover( 1253): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/LocalBluetoothProfileManager( 3786): setBluetoothStateOff
,D/HtcTagManager( 3786): stopProxy
W/BluetoothEventManager( 3786): unregister mProfileBroadcastReceiver fail
I/QuickSettingWifi( 1113): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
I/IntentController( 1113): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothMasReceiver( 1604): Bluetooth STATE CHANGED to 10
V/BluetoothMasService( 1604): onDestroy: mIsEmailEnabled: true
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
,D/TetherPref( 3786): persistRestoreBluetoothState false
D/PMS     (  903): acquireWL(42530ca8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3786 1000 null
W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/HtcBtWidget_BTWidgetProvider( 4669): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4669): updateWidget(context) for widget: 
D/PMS     (  903): releaseWL(42530ca8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  903): acquireWL(434a0e90): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3786 1000 null
,D/DockEventReceiver( 3786): finishStartingService: stopping service
,D/PMS     (  903): releaseWL(434a0e90): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothMasReceiver( 1604): Bluetooth STATE CHANGED to 10
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1779): Received state change = 10
,D/BluetoothAdapter( 1113): 1104326464: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1113): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,W/System.err(  903): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43e77660:true
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4703): new LocationAgent instance!!
,D/HtcTagManager( 4703): HtcTagManager construction complete
,D/BluetoothAdapter( 4703): 1101589064: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 4703): BluetoothInputDevice()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4703): 1101589064: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 4703): BluetoothInputDevice(): Fake return onServiceConnected
D/BluetoothManagerService(  903): Registered receivers: 12
D/HidProfile( 4703): Bluetooth service connected
,W/BluetoothInputDevice( 4703): Proxy not attached to service
,D/BluetoothPan( 4703): BluetoothPan()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4703): 1101589064: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  903): Registered receivers: 13
D/BluetoothPan( 4703): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 4703): Bluetooth service connected
,D/BluetoothMap( 4703): Create BluetoothMap proxy object
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 14
,E/BluetoothMap( 4703): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 15
,D/BluetoothSap( 4703): BluetoothSap() call bindService
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 4703): BluetoothPbap()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4703): 1101589064: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 4703): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4703): Bluetooth service connected
D/LocalBluetoothProfileManager( 4703): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 4703): 1101589064: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  903): Registered receivers: 16
D/BluetoothAdapter( 4703): 1101589064: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4703): setBluetoothStateOff
D/HtcTagManager( 4703): stopProxy
W/BluetoothEventManager( 4703): unregister mProfileBroadcastReceiver fail
,I/ActivityManager(  903): Killing 3857:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=3857
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3857
,D/MediaRouterService(  903): Client com.google.android.music (pid 3857): Died!
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4720 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/PMS     (  903): acquireWL(42cc0c60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  903): NoActiveNetworkState
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  903): bSetPropertyMultiRAB:false
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0,
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1460/10028)
D/PMS     (  903): releaseWL(42cc0c60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4442/10078)
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1882/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4412/10026)
,I/MusicStore( 4720): Database version: 95
,W/ContextImpl( 4720): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4720): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4720): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Netd    (  364): No subsystem found in netlink event
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4720): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
V/Tethering(  903): remove iface:wlan0
D/Tethering(  903): interfaceRemoved wlan0
E/Tethering(  903): attempting to remove unknown iface (wlan0), ignoring
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4720): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4720, uid=10154, userID:0
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.music (pid 4720): Registered
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,I/MediaRouter( 4720): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (4720/10154)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2429/10021)
,D/PMS     (  903): acquireWL(437d8d60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1220 10028 null
D/MediaRouter( 4720): getSelectedRoute
,D/PMS     (  903): acquireWL(42595c08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1220 10028 null
D/PMS     (  903): releaseWL(437d8d60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4720/10154)
,I/NetworkMonitor( 4720): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1220/10028)
,D/PMS     (  903): releaseWL(42595c08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4720, uid=10154, userID:0
,D/Process (  903): killProcessQuiet, pid=4442
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4442:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  903): Recipient 4442
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/BroadcastQueue(  903): Exception when sending broadcast to ComponentInfo{com.google.android.setupwizard/com.google.android.setupwizard.MobileConnectivityChangeReceiver}
W/BroadcastQueue(  903): android.os.DeadObjectException
W/BroadcastQueue(  903): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  903): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  903): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  903): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  903): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:15076)
W/BroadcastQueue(  903): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:401)
W/BroadcastQueue(  903): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
W/BroadcastQueue(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/BroadcastQueue(  903): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4744 uid=10078 gids={50078, 3003, 5012}
,I/ActivityManager(  903): Process com.google.android.setupwizard (pid 4442) has died and restarted (pid 4744).
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): Util - no network available!
D/Tethering(  903): interfaceLinkStateChanged p2p0, false
,D/Tethering(  903): interfaceStatusChanged p2p0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/AutoSetting( 1396): service - onCreate()
D/AutoSetting( 1396): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  903): request 41ec6ed8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  903): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1396): service - mHandler: cancel location update
D/AutoSetting( 1396): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4744): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4744): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4744): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4744): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4744/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4744/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4744/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4473/10151)
,I/dalvikvm-heap( 4114): Grow heap (frag case) to 15.216MB for 1821008-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4114/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4114): Grow heap (frag case) to 16.949MB for 1821008-byte allocation
,W/Netd    (  364): No subsystem found in netlink event
,V/Tethering(  903): remove iface:p2p0
D/Tethering(  903): interfaceRemoved p2p0
,E/Tethering(  903): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=-2s134ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  903): releaseWL(435f3c00): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/WifiP2pService(  903): P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,D/PMS     (  903): acquireWL(42fe0c80): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4720 10154 null
,W/ContextImpl( 4720): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4720): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4720, uid=10154, userID:0
,I/MusicLeanback( 4720): Conditions not met for autocaching.
,I/MusicLeanback( 4720): Stop autocaching.
D/PMS     (  903): releaseWL(42fe0c80): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43853e38 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WirelessDisplayService(  903): HANDLE_WIFI_DIS
,D/WirelessDisplayService(  903): HANDLE_STOP_DIS
D/WirelessDisplayService(  903): clearDongleCache: Wivulist is already empty
,D/WirelessDisplayService(  903): HANDLE_CHANGE_STATE previousState = 1, state=1 err=-1
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(43153690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=469649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43153690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42d92420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(42d92420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1396): service - handleMessage() stop self
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/AutoSetting( 1396): service - onDestroy() END
,D/Process (  903): killProcessQuiet, pid=4590
,I/ActivityManager(  903): Killing 4590:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 4590
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,D/PMS     (  903): acquireWL(43006988): PARTIAL_WAKE_LOCK  Icing 0x1 1220 10028 null
,D/PMS     (  903): releaseWL(43006988): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(429743d0): PARTIAL_WAKE_LOCK  Icing 0x1 1220 10028 null
,D/PMS     (  903): releaseWL(429743d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(436e5a80): PARTIAL_WAKE_LOCK  Icing 0x1 1220 10028 null
,D/PMS     (  903): releaseWL(436e5a80): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(43bcec70): PARTIAL_WAKE_LOCK  Icing 0x1 1220 10028 null
,D/PMS     (  903): releaseWL(43bcec70): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(43727758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43727758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): releaseWL(42376698): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43ef4740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=529650, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43ef4740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43059068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(43059068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43739470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43739470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43d09758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=589649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43d09758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43337c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(43337c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43042220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43042220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1237): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1237): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1237): sku_id=99
D/ContactMessageStore( 1237): start background delete task...
,D/ContactMessageStore( 1237): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1237): size: 0 , 0
,D/ContactMessageStore( 1237): Background delete complete
,I/ActivityManager(  903): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=4776 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,D/PMS     (  903): acquireWL(4354f8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
V/AlarmManager(  903): sending alarm PendingIntent{43a0f5e0: PendingIntentRecord{41c28d80 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449681706467, Int=0
,D/PMS     (  903): releaseWL(4354f8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4776, uid=10073, userID:0
,D/Finsky  ( 4776): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4776/10073)
,D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4776/10073)
,D/Finsky  ( 4776): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4776): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4776): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4776, uid=10073, userID:0
,D/Finsky  ( 4776): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4776): [1] 2.run: Finished loading 1 libraries.
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,D/Finsky  ( 4776): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,D/Finsky  ( 4776): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4776): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4776): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/PMS     (  903): acquireWL(43afb450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
,V/AlarmManager(  903): sending alarm PendingIntent{43853c48: PendingIntentRecord{41c28d80 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449681707938, Int=0
,D/PMS     (  903): releaseWL(43afb450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4776): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4776): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4776): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4776): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4776): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/Process (  903): killProcessQuiet, pid=4548
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4548:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4548
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4776): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4776): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4776): [1] DailyHygiene.reschedule: Scheduling new run in 87 minutes (failures=3)
,D/PMS     (  903): acquireWL(422c7020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=649648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(422c7020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43eb8788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43eb8788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42590c28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
,V/AlarmManager(  903): sending alarm PendingIntent{422d96f8: PendingIntentRecord{42572048 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449681723150, Int=0
,D/PMS     (  903): releaseWL(42590c28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4776): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  903): acquireWL(4244c140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4244c140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(425ebbe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=709649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425ebbe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  903): killProcessQuiet, pid=4631
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4631:com.htc.aurora/u0a47 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4631
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(436ab7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(436ab7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43b59ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/BatteryService(  903): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(43b59ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(436376b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=769649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(436376b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4256ce88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(4256ce88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4335ba18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{43fae428: PendingIntentRecord{43be7920 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=710622, Int=300000
,V/AlarmManager(  903): sending alarm PendingIntent{41cfcf90: PendingIntentRecord{423b04f8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784523, Int=0
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,D/PMS     (  903): releaseWL(4335ba18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): acquireWL(42fdd0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42fdd0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42530730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=829648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42530730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43b366d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43b366d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4349eee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4349eee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43f90830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=889649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43f90830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(434220e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(434220e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-,
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42efedb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42efedb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1365): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1365): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1365): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1365): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1365): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 4776): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4776): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4776): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4776): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4776): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41f05be8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 2 11 3 12
,D/libc    ( 4776): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4776): [NET] getaddrinfo-,err=8
D/libc    ( 4776): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4776): [NET] getaddrinfo-, 1
,D/libc    ( 4776): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =828f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =828f (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=828f, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 4776): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4776): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  903): acquireWL(4255bee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=949648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4255bee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43bc0cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43bc0cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42fdb8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(42fdb8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43f5b040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1009648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43f5b040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43f18038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42469d10: PendingIntentRecord{4247e5b0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449682011201, Int=900000
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4831 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/AlarmManager(  903): sending alarm PendingIntent{41fbc2f8: PendingIntentRecord{43764d40 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449682081324, Int=0
,W/ContextImpl( 4831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4831): call getInstance()
,D/PMS     (  903): acquireWL(43411228): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4831 1000 null
,D/SmartSyncUtils( 4831): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4831): MY_DEBUG = false
,D/PMS     (  903): releaseWL(43f18038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): releaseWL(43411228): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(424cc960): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4831 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4831): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4831): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4831): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4831): SettingOnTime = 1449698400000, randomSettingOnTime = 1449695238000
,D/SmartSyncScreenOnOffTimeReceiver( 4831): SettingOffTime = 1449687600000, randomSettingOffTime = 1449692782000
,D/SmartSyncScreenOnOffTimeReceiver( 4831): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 4831): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4831): bNightModeTurnOffOnce = false
,D/PMS     (  903): releaseWL(424cc960): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/Process (  903): killProcessQuiet, pid=4686
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4686:com.htc.widget.process2/u0a48 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4686
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(43f74df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43f74df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43baa148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(43baa148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(439ea480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1069649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(439ea480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(438eed98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(438eed98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(435bac68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(435bac68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(435ba990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1129649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(435ba990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43599890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43599890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(434a3b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(434a3b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43308470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1189649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43308470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(432d25c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(432d25c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(432985a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(432985a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,W/GLSActivity( 1365): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1365): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1365): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1365): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1365): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41f90a60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4776): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4776): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4776): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4776): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4776): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1113): com.google.android.gms 2 18 4 12
D/libc    ( 4776): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4776): [NET] getaddrinfo-,err=8
,D/libc    ( 4776): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4776): [NET] getaddrinfo-, 1
D/libc    ( 4776): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7d99 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =7d99 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=7d99, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 4776): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4776): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  903): acquireWL(425318c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1249648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425318c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(423930d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(423930d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(423e30a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
,D/HtcPowerSaver(  903): updateBatteryInfo
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(423e30a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42cc08a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1309648, Int=0
,D/PMS     (  903): releaseWL(42cc08a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(424df108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  903): n_update end
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(424df108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42f05448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1369648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42f05448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42517978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42517978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderNotification, total:1
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  903): batLight: plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c80000
D/qdlights(  903): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1113): closing low battery warning: level=98
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/ContextImpl( 4831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3786): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3786): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3786): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3786): Cust_ConnectToPC   : spcsc>false
D/        ( 3786): Cust_ConnectToPC   : IPT>true
D/        ( 3786): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3786): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3786): Index of the first 1 = -1
,W/Settings( 3786): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3786): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3786): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3786): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3786): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(423d0f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(423d0f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=98
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42f72e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42f72e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(425134d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1429648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425134d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(422bbfe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/BatteryService(  903): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=98
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(422bbfe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42366248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42366248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42fe0878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1489649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42fe0878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42b98f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42b98f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1365): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1365): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1365): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1365): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1365): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,E/PlayEventLogger( 4776): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4776): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4776): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4776): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4776): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41ac7010 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4776): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4776): [NET] getaddrinfo-,err=8
D/libc    ( 4776): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4776): [NET] getaddrinfo-, 1
,D/libc    ( 4776): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
I/RemoteViews.Performance( 1113): com.google.android.gms 1 13 4 12
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c336 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =c336 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=c336, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 4776): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4776): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname),
,D/PMS     (  903): acquireWL(42569170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1549649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42569170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4253b4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4253b4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42439da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42439da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=99
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4373d138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1609649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4373d138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(422e67b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(422e67b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(425d8958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1669649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425d8958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43bac7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43bac7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,D/PMS     (  903): acquireWL(423e2058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41cfcf90: PendingIntentRecord{423b04f8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1504547, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{41ca5e68: PendingIntentRecord{42411c40 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1693651, Int=0
,D/PMS     (  903): acquireWL(42527d98): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): releaseWL(423e2058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42567358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): releaseWL(42527d98): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(42567358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(438d8658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(438d8658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(42f08978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1729649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42f08978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42892f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42892f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(4247d7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4247d7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
V/NotificationService(  903): batLight: Full, plugged
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1568): [EventService] reorderNotification, total:0
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 4831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,D/TetherSettings( 3786): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3786): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3786): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3786): Cust_ConnectToPC   : spcsc>false
D/        ( 3786): Cust_ConnectToPC   : IPT>true
D/        ( 3786): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3786): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3786): Index of the first 1 = -1
W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3786): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3786): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3786): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3786): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4257d4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1789649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4257d4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(42f03238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42f03238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,I/ProcessStatsService(  903): Prepared write state in 51ms
,I/ProcessStatsService(  903): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-33-58.bin
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1365): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1365): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1365): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1365): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1365): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1113): com.google.android.gms (false,0)
,E/PlayEventLogger( 4776): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4776): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4776): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4776): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4776): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4776): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 4776): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4776): [NET] getaddrinfo-,err=8
D/libc    ( 4776): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4776): [NET] getaddrinfo-, 1
D/libc    ( 4776): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41eff980 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    (  364): [NET] +++++ res_nsend xid =44c3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =44c3 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=44c3, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 4776): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4776): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1113): com.google.android.gms 4 12 3 12
,D/PMS     (  903): acquireWL(425dfd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1849648, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425dfd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43739770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43739770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(425b2a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41f66d00: PendingIntentRecord{41f5fea8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1909649, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425b2a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4876): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4876): ====startRecUseTime====
D/htc.customization.log.level( 4876):  is 
W/CustomizationLogLevel( 4876): Level value is invalid, use default level 2
D/CustomizationManager( 4876):  Read ACC file spent 0.097 (s)
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4876): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4876): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4876): Parsing tag category name = system
I/CustomizationCIDLoader( 4876): Parsing tag category name = application
I/CustomizationCIDLoader( 4876): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4876): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4876): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4876): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4876): Parsing tag category name = Settings
D/CustomizationManager( 4876):  Read CID file spent 0.150 (s)
D/CustomizationManager( 4876):  All configurations done spent 0.151 (s)
W/HtcNativeFlag( 4876): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4876): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4876): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4876): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4876, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  903): killProcessQuiet, pid=4342
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  903): Killing 4342:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  903):   Force finishing activity ActivityRecord{4202f028 u0 com.test.thalitest/.MainActivity t2}
W/PackageSettings(  903): Skipping PackageSetting{4220b028 com.example.hello/10355} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 4342 uid 10348
E/JavaBinder( 1207): !!! FAILED BINDER TRANSACTION !!!
I/acms    ( 1882): Unregistering com.test.thalitest
E/acms    ( 1882): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1568): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1568): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1460): Ignoring removeGeofence because network location is disabled.
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
D/PMS     (  903): acquireWL(43efdaf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1460 10028 null
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  903): WIN DEATH: Window{42360a30 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  903): Client connection lost with reason: 4
D/PMS     (  903): releaseWL(43efdaf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
D/VoicemailCleanupService( 1293): Cleaning up data for package: com.test.thalitest
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PackageBroadcastService( 1220): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/Launcher( 1267): Deferring update until onResume
D/Launcher( 1267): waitUntilResume // bindAppsRemoved
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4892 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1326): Unsupported attribute readOnly
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/MultiDex( 4892): install
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/MultiDex( 4892): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/MultiDex( 4892): loading existing secondary dex files
I/MultiDex( 4892): load found 1 secondary dex files
I/MultiDex( 4892): install done
I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4909 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
D/PhoneApp( 1237): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1220): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1220, uid=10028, userID:0
I/ProviderInstaller( 4892): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/Icing   ( 1220): doRemovePackageData com.test.thalitest
D/PMS     (  903): acquireWL(4349e2a8): PARTIAL_WAKE_LOCK  Icing 0x1 1220 10028 null
D/PMS     (  903): releaseWL(4349e2a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4909): install
I/MultiDex( 4909): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4909): loading existing secondary dex files
I/MultiDex( 4909): load found 1 secondary dex files
I/MultiDex( 4909): install done
I/ProviderInstaller( 4909): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  903): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1396): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1396): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1267): action: android.intent.action.PACKAGE_REMOVED
D/Process (  903): killProcessQuiet, pid=4669
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4669:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
I/IcingCorporaProvider( 2878): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  903): Recipient 4669
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4930 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  903): acquireWL(422a21a8): PARTIAL_WAKE_LOCK  Icing 0x1 1220 10028 null
W/PackageManager(  903): Unable to load service info ResolveInfo{42292a20 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
I/IcingCorporaProvider( 2878): UpdateCorporaTask done [took 157 ms] updated apps [took 157 ms] 
E/SQLiteLog( 4892): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4892): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9c5460
E/DriveAsyncService( 4892): disk I/O error (code 3850)
E/DriveAsyncService( 4892): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4892): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4892): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4892): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4892): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4892): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4892): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4892): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4892): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4892): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4892): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4892): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4892): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4892): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4892): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9c5460
E/DocListDatabase( 4892): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4892): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4892): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4892): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4892): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4892): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4892): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4892): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4892): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4892): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4892): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4892): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4892): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4892): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4892): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4892): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4892): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4892): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4892): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4892): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4892): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4892): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4892): threadid=1: thread exiting with uncaught exception (group=0x4164de30)
E/AndroidRuntime( 4892): FATAL EXCEPTION: main
E/AndroidRuntime( 4892): Process: com.google.android.gms.drive, PID: 4892
E/AndroidRuntime( 4892): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4892): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4892): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4892): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4892): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4892): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4892): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4892): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4892): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4892): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4892): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4892): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4892): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4892): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4892): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4892): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4892): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4892): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4892): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4892): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4892): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4892): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4892): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4892): 	... 10 more
E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
D/Process ( 4892): killProcess, pid=4892
D/Process ( 4892): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
E/SQLiteDatabase( 4930): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4930): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4930): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4930): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4930): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4930): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4930): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4930): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4930): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4930): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4930): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4930): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4930): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4930): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4930): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4930): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4930): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4930): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4930): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4930): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4930): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4930): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4930): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4930): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4930): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4930): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4930): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4930): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4930): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4930): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4930): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4930): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4930): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4930): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4930): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4930): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4930): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4930): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4930): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4930): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4930): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4930): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4930): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4930): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4930): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4930): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4930): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4930): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4930): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4930): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4930): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4930): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4930): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4930): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4930): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4930): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4930): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4930): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4930): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4930): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4930): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4930): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4930): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4930): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4930): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4930): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4930): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4930): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4930): threadid=11: thread exiting with uncaught exception (group=0x4164de30)
E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/AndroidRuntime( 4930): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4930): Process: com.google.android.apps.docs, PID: 4930
E/AndroidRuntime( 4930): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4930): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4930): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4930): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4930): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4930): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4930): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4930): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4930): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/Process ( 4930): killProcess, pid=4930
D/Process ( 4930): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4952 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Recipient 4930
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4930) has died.
I/ActivityManager(  903): Recipient 4892
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 4892) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
W/ContextImpl( 4952): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
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
W/dalvikvm( 4952): threadid=10: thread exiting with uncaught exception (group=0x4164de30)
I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4965 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
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
E/ActivityManager(  903): App crashed! Process: com.android.keychain
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4952): killProcess, pid=4952
D/Process ( 4952): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449682983232.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
I/ActivityManager(  903): Recipient 4952
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.android.keychain (pid 4952) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10890ms
D/AppTag  ( 4965): getInstance(Context context)
D/AppTag  ( 4965): getInstance(Context context)
D/AppTag  ( 4965): onCreate()
D/PMS     (  903): acquireWL(4251b438): PARTIAL_WAKE_LOCK  AsyncService 0x1 4114 10160 null
D/PMS     (  903): releaseWL(4251b438): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4983 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4983): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4983 dbg=false s=true
I/DeviceManagement( 4983): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4983): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4983): WorkflowService: Starting workflow service
I/DeviceManagement( 4983): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41aa9e40] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4983): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4983): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4983): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4983): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  903): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4997 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4983): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4983): SessionStateController: Checking invariants...
D/Documents( 4997): Loading roots for com.android.providers.downloads.documents
D/Documents( 4997): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4997): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4997): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4997): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4997): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4997): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4997): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4997): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4997): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4997): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4997): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4997): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4997): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4997): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4997): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4997): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4997): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4997): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4997): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4997): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4997): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4997): threadid=1: thread exiting with uncaught exception (group=0x4164de30)
E/AndroidRuntime( 4997): FATAL EXCEPTION: main
E/AndroidRuntime( 4997): Process: com.android.documentsui, PID: 4997
E/AndroidRuntime( 4997): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4997): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4997): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4997): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4997): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4997): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4997): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4997): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4997): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4997): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4997): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4997): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4997): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4997): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4997): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4997): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4997): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4997): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4997): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4997): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4997): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4997): 	... 10 more
I/ActivityManager(  903): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5011 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process (  903): killProcessQuiet, pid=1604
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 1604:com.android.bluetooth/1002 (adj 15): empty #17
E/ActivityManager(  903): App crashed! Process: com.android.documentsui
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/Process (  903): killProcessQuiet, pid=1779
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  903): Killing 1779:com.htc.bluetooth.le.profiles/1002 (adj 15): empty #17
I/ActivityManager(  903): Recipient 1604
D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449682983499.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
D/Process ( 4997): killProcess, pid=4997
D/Process ( 4997): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Recipient 1779
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  903): Recipient 4997
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.android.documentsui (pid 4997) has died.
I/ActivityManager(  903): Resuming delayed broadcast
D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ExternalStorage( 5011): After updating volumes, found 1 active roots
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  903): Resuming delayed broadcast
E/SQLiteDatabase( 4983): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4983): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4983): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4983): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4983): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4983): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4983): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4983): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4983): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4983): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4983): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4983): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 4983): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4983): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4983): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4983): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4983): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4983): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4983): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5027 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4983): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4983): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4983): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4983): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4983): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4983): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4983): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4983): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4983): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4983): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4983): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4983): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4983): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4983): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
