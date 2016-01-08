#### Test 549702610b97681_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system,
V/LightsService(  911): setLight #0: color=#26
V/LightsService(  911): setLight #0: color=#22
V/LightsService(  911): setLight #0: color=#1c
V/LightsService(  911): setLight #0: color=#15
V/LightsService(  911): setLight #0: color=#14
--------- beginning of /dev/log/main
E/cutils-trace( 4472): Error opening trace file: No such file or directory (2)
D/WIFI_ICON( 1118): WifiActivity: 1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/CustomizationManager( 4472): ====startRecUseTime====
D/htc.customization.log.level( 4472):  is 
W/CustomizationLogLevel( 4472): Level value is invalid, use default level 2
D/CustomizationManager( 4472):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4472): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4472): Parsing tag category name = system
I/CustomizationCIDLoader( 4472): Parsing tag category name = application
I/CustomizationCIDLoader( 4472): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4472): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4472): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4472): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4472): Parsing tag category name = Settings
D/CustomizationManager( 4472):  Read CID file spent 0.097 (s)
D/CustomizationManager( 4472):  All configurations done spent 0.097 (s)
W/HtcNativeFlag( 4472): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4472): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4472): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4472): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4472
D/PMS     (  911): acquireHCC(437bca70): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(437b7828): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1137288472
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d5ed98
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
D/PMS     (  911): acquireWL(437b3540): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/ActivityManager(  911): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4483 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1274): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4483): Binding Chromium to main looper Looper (main, tid 1) {41b12f68}
I/LibraryLoader( 4483): Expected native library version number "",actual native library version number ""
I/chromium( 4483): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4483): Initializing chromium process, renderers=0
D/PMS     (  911): acquireWL(43090d20): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  911): acquireWL(42ffed98): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  911): releaseWL(43090d20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4255e2c0:true
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4483): 1102221000: getState(). Returning 12
I/Adreno-EGL( 4483): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4483): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4483): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4483): Local Branch: 
I/Adreno-EGL( 4483): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4483): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4483):                  aa63bbd948f41d15fc72f585e
W/chromium( 4483): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4483): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4483): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4483): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4483): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4483): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4483): CordovaWebView is running on device made by: HTC
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 91
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
,W/AwContents( 4483): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  911): Disable input method client, pid=1274
W/ResourceType( 4483): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4483): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b5a578, mServedView=org.apache.cordova.engine.SystemWebView{41b201e0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4483): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  911): Enable input method client, pid=4483
I/ActivityManager(  911): Displayed com.test.thalitest/.MainActivity: +292ms
D/PMS     (  911): releaseWL(437b3540): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4483): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4483): JniHelper::setJavaVM(0x415eb048), pthread_self() = 1663146016
D/JX-Cordova( 4483): jxcore cordova android initializing
D/WIFI_ICON( 1118): WifiActivity: 0
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.582MB for 95956-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.661MB for 143930-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.781MB for 215890-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.955MB for 323830-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 12.223MB for 485740-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 13.226MB for 1092904-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 14.133MB for 1639352-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 15.467MB for 2459024-byte allocation
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
D/PMS     (  911): releaseHCC(437bca70): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  911): releaseHCC(437b7828): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 17.575MB for 3688532-byte allocation
,W/jxcore-log( 4483): Initializing JXcore engine
,W/jxcore-log( 4483): JXcore engine is ready
,W/jxcore-log( 4483): Starting JXcore engine
,W/jxcore-log( 4483): Platform android
W/jxcore-log( 4483): 
,W/jxcore-log( 4483): Process ARCH arm
W/jxcore-log( 4483): 
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  911): releaseWL(42ffed98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 110
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/jxcore-log( 4483): JXcore Cordova bridge is ready!
I/jxcore-log( 4483): 
,W/jxcore-log( 4483): JXcore engine is started
,I/chromium( 4483): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4483): Toggling radios to true
I/jxcore-log( 4483): 
,D/BluetoothAdapter( 4483): enable(): BT is already enabled..!
,D/WifiManager( 4483): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  911): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  911): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  911): Settings:Agentvalue: 2
W/Settings:Agent(  911): >> traceCallingStack()
W/Settings:Agent(  911): Process.myPid(): 911
W/Settings:Agent(  911): Process.myTid(): 1456
W/Settings:Agent(  911): Process.myUid(): 1000
W/Settings:Agent(  911): 
W/Settings:Agent(  911): 
,W/System.err(  911): java.lang.Throwable: stack dump
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  911): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  911): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  911): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  911): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  911): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  911): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  911): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  911): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  911): 
,W/Settings:Agent(  911): << traceCallingStack(): 2(ms)
,D/WifiManager( 4483): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  911): doBoolean: DISCONNECT
D/WifiManager( 4483): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): TDLS: Tear down peers,
,I/wpa_supplicant( 1186): wpa_driver_nl80211_disconnect(reason_code=3),
D/WifiService(  911): New client listening to asynchronous messages
D/WifiService(  911): setWifiEnabled: true pid=4483, uid=10389
E/WifiService(  911): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  911): isSprintWifiRestricted(): false
,I/WifiService(  911): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  911): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
I/jxcore-log( 4483): Radios toggled
I/jxcore-log( 4483): 
I/jxcore-log( 4483): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4483): 
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1186): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1186): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1186): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  911): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  911): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1186): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/HTCRequest(  911): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  911): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  911): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7979bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1186):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1186): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1186): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1186): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  911): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1186): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1186): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  911):    returned true
D/WifiPerfLock(  911): release()
,D/WifiStateMachine(  911): PerfLock released for exiting ConnectedState
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1186): Power_Mode_Type mode = 0
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/ConnectivityService(  911): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  911): acquireWL(41f74e50): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 911 1000 null
D/WifiP2pService(  911): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911):    returned true
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  911): [RunningState] Stop DHCP
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  911): doBoolean: RECONNECT
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): Fast associate: Old scan results
I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): Enter handleNetworkDisconnect
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20672 mDataStallAlarmIntent=PendingIntent{4263dd20: PendingIntentRecord{4254c758 android broadcastIntent}}
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 0
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  911):    returned true
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  911): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3841): >>>>>WISPrService start isConnected = false<<<<<
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  911): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  911): Provision feature enable=false
,D/ConnectivityService(  911): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  911): Exit handleNetworkDisconnect
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  911): isAvailable+-
D/UsbnetStateTracker(  911): reconnect
,D/UsbnetStateTracker(  911): isAvailable+-
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  911): default: reconnect()
D/MDST    (  911): default: setTeardownRequested(false)
D/MDST    (  911): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  911): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  911): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3841): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  911): New client listening to asynchronous messages
D/ConnectivityService(  911): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/WISPrService( 3841): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3841): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1381): Read error: ssl=0x6413f008: I/O error during system call, Connection timed out
D/libc    (  362): [NET] entry_id:3   entry:0xb855b188  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb855b048  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb855b428  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb855b250  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb855b4f0  removed 
D/libc    (  362): [NET] entry_id:6   entry:0xb8557008  removed 
,D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
D/ConnectivityService(  911): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): handleConnectivityChange: resetting
D/ConnectivityService(  911): resetConnections(wlan0, 3)
D/ConnectivityService(  911): flush DNS cache for net 1(wlan0)
,V/NativeCrypto( 1381): SSL shutdown failed: ssl=0x6413f008: I/O error during system call, Broken pipe
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  911): acquireWL(42487928): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  911): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  911): acquireWL(4261a7c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
I//system/bin/ip(  362): RTNETLINK answers: No such process
D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  911): startScan Pid: 911 Uid 1000
,D/WifiNative-wlan0(  911): doBoolean: SCAN
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1186): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
D/BatSI   (  911): WIFI scan started for: 650a0300 uid:1000
,D/ConnectivityService(  911): reportInetCondition for net -1, percentage: 0 by  (1381/10029)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  911):    returned false
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
D/PMS     (  911): releaseWL(42487928): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): mActiveDefaultNetwork: -1
D/ConnectivityService(  911): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/PMS     (  911): releaseWL(4261a7c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  911): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4534 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/Tethering(  911): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  911): bSetPropertyMultiRAB:false
D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  911): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  911): ipv4Default null
I/Tethering(  911): No IPv4 upstream interface, giving up.
D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/CaptivePortalTracker(  911): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  911): NoActiveNetworkState
I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
D/GpsLocationProvider(  911): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(42e81320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4332/10100)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4332/10100)
D/PMS     (  911): releaseWL(42e81320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,I/MusicStore( 4534): Database version: 95
,W/ContextImpl( 4534): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4534): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4534): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4534): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4534): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4534, uid=10154, userID:0
,D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
,D/MediaRouterService(  911): Client com.google.android.music (pid 4534): Registered
,I/MediaRouter( 4534): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2401/10021)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.music (4534/10154)
,I/ActivityManager(  911): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4554 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4534): getSelectedRoute
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (4534/10154)
I/NetworkMonitor( 4534): type=WIFI subType= reason=null isConnected=false
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4534, uid=10154, userID:0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(43b61878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(43b61878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  911): killProcessQuiet, pid=3874
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Killing 3874:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ACRA    ( 4554): ACRA is enabled for com.facebook.katana, intializing...
D/ACRA    ( 4554): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4554): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/ActivityManager(  911): Recipient 3874
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4554): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4554): Preparing secondary program dexes.
V/DexLibLoader( 4554): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4554): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4554): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4554): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4554): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4554): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4554): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4554): Dex already copied
D/OdexVerifier( 4554): Odex verification is skipped.
,V/DexLibLoader( 4554): Creating class loader
V/DexLibLoader( 4554): Finished creating class loader
V/DexLibLoader( 4554): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4554): Dex already copied
D/OdexVerifier( 4554): Odex verification is skipped.
,V/DexLibLoader( 4554): Creating class loader
,V/DexLibLoader( 4554): Finished creating class loader
V/DexLibLoader( 4554): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4554): Dex already copied
D/OdexVerifier( 4554): Odex verification is skipped.
,V/DexLibLoader( 4554): Creating class loader
,V/DexLibLoader( 4554): Finished creating class loader
V/DexLibLoader( 4554): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4554): Dex already copied
D/OdexVerifier( 4554): Odex verification is skipped.
,V/DexLibLoader( 4554): Creating class loader
V/DexLibLoader( 4554): Finished creating class loader
,V/DexLibLoader( 4554): Verifying classes from secondary dexes.
,D/DexLibLoader( 4554): DexLibLoader.ensureDexLoaded took 17 ms,
,W/dalvikvm( 4554): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4554): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4554): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4554): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4554): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4554): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4554): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1186): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1186): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
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
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
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
D/wpa_supplicant( 1186): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb797b4e8  current_ssid=0x0
D/wpa_supplicant( 1186): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1186): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1186): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1186): check if in concurrent case
,I/wpa_supplicant( 1186): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 1186): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1186): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1186): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1186): RSN: PMKSA cache search - network_ctx=0xb797b4e8 try_opportunistic=0
D/wpa_supplicant( 1186): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1186): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1186): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1186): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 1186): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1186): nl80211: Unsubscribe mgmt frames handle 0xb797a718 (mode change)
D/wpa_supplicant( 1186): nl80211: Subscribe to mgmt frames with non-AP handle 0xb797a718
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb797a718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1186):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1186):   * freq=2412
,D/wpa_supplicant( 1186):   * Auth Type 0
D/wpa_supplicant( 1186):   * WPA Versions 0x2
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1186): nl80211: Connect request send successfully
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (351) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000104871039
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-55
I/wpa_supplicant( 1186): tsf=0000000104871055
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=2
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-55
I/wpa_supplicant( 1186): tsf=0000000104871051
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiStateMachine(  911): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  911): == (3) end of scan result ==
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 104871039, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 104871055, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 104871051, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
D/BatSI   (  911): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1186): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
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
I/wpa_supplicant( 1186): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1186): Get randomness: len=32 entropy=4
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  911): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  911): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412,
D/HTCRequest(  911): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
D/Tethering(  911): interfaceStatusChanged wlan0, true
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  911): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  911): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  911): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  911): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  911): Enter handleAssociatedWithEvent
D/WifiStateMachine(  911): Associated
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  911): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  911): Exit handleAssociatedWithEvent
,D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  911): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  911): updateConnectedAP...,
I/wpa_supplicant( 1186): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb797a9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16,
D/wpa_supplicant( 1186):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 1186): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef9b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1186):    broadcast key
D/WifiApDatabaseHandler(  911): updateConnectedAP...
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1186): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1186): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1186): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1186): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1186): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=6
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
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state IDLE,
D/wpa_supplicant( 1186): EAPOL authentication completed successfully
I/wpa_supplicant( 1186): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
,D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
D/Tethering(  911): interfaceStatusChanged wlan0, true
D/Tethering(  911): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiStateMachine(  911): This record is existed, only update it...
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700,
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiMonitor(  911): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  911): updateConnectedAP...
,D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  911): updateConnectedAP...
,D/WifiStateMachine(  911): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  911): This record is existed, only update it...
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  911): updateConnectedAP...
,D/WISPrService( 3841): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  911): Provision feature enable=false
,D/ConnectivityService(  911): mActiveDefaultNetwork: -1
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
,D/WISPrService( 3841): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  911): [StoppedState] Start DHCP
,D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 1
D/WifiStateMachine(  911): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  911): acquireWL(426809e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 911 1000 null
,D/WifiStateMachine(  911): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 1
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  911):    returned null
E/WifiStateMachine(  911): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  911):    returned null
D/WifiP2pService(  911): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222e960 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222e960 target=com.android.internal.util.StateMachine$SmHandler }
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,W/dalvikvm( 4554): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4554): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4554): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4554): Verify
,D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiService(  911): New client listening to asynchronous messages
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4554): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4554): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421430e0
,W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  911): Couldn't get kernel wake lock stats
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421430e0, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422734d0
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@41c1ab70
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,I/dalvikvm-heap( 4554): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,W/PMS     (  911): mWirelessDisplayManager is null
D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/Process (  911): killProcessQuiet, pid=4268
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 4268:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4268
,D/AutoSetting( 1318): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/WifiService(  911): Client connection lost with reason: 4
,I/ActivityManager(  911): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4604 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
,D/AutoSetting( 1318): Util - no network available!
,D/AutoSetting( 1318): service - onCreate()
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
D/AutoSetting( 1318): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  911): request 42603b60 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1318): service - mHandler: cancel location update
D/AutoSetting( 1318): service -           changes count: 0
,D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1186): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): handlePostDhcpSetup release wake lock during DHCP
,W/fb4a(:<default>):UserScope( 4554): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiP2pService(  911): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  911): releaseWL(426809e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/fb4a(:<default>):ViewerContextManagerForUserScope( 4554): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1186): Change stage from stage0 to stage3
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true,
,D/WifiStateMachine(  911): gateway: /192.168.1.1
,D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
W/fb4a(:<default>):UserScope( 4554): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  911): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1186): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  911): VerifyingLinkState enter
D/WifiStateMachine(  911): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  911): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  911): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,V/NetworkPolicy(  911): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20674 delay=15s
,D/WifiWatchdogStateMachine(  911): WAN detection
,D/WISPrService( 3841): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  911): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  911): default: teardown()
D/MDST    (  911): default: setTeardownRequested(true)
D/MDST    (  911): default: setEnableApn apnType =default , enable=false
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/MDST    (  911): default: setTeardownRequested(true)
D/ConnectivityService(  911): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
E/ConnectivityService(  911): Unexpected mtu value: android.net.wifi.WifiStateTracker@4249bb20
D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  911): syncGetConfiguredNetworks
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
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
D/ConnectivityService(  911): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  911): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  911): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  911): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  911):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  911): handleConnectivityChange: resetting
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  911): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  911): acquireWL(4320ea30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
D/ConnectivityService(  911): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(4320ea30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  911): mActiveDefaultNetwork: WIFI
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 311ms
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4340d978)
D/NfcService( 1259): ScreenObserver: OFF
I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1259): applyRouting - 0
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
D/PMS     (  911): OOBE c monitor 11
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
D/PMN     (  911): wakingUp
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
I/InputMethodManagerService(  911): Disable input method client, pid=4483
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
D/AlarmManager(  911): ACTION_SCREEN_ON
I/WindowManager(  911): No lock screen! windowToken=null
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
D/NfcService( 1259): applyRouting -2
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20675 delay=15s
,D/NfcService( 1259): applyRouting - 0
D/PMS     (  911): acquireWL(42e340b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  911): acquireWL(42654990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/PMN     (  911): onScreenOn
D/PMS     (  911): releaseWL(42e340b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  911): releaseWL(42654990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): acquireWL(430de568): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
,D/NfcService( 1259): applyRouting -2
,D/MtpService( 2401): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2401): [MTP][onReceive]-
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  911): releaseWL(430de568): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): SET_SCREEN_ON:On
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1186): BG scan when screen On
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): Match BG scan, scan!
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  911):    returned true
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1186): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1186): EAPOL: disable timer tick
D/MobileConnectivityChangeReceiver( 4604): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/MobileConnectivityChangeReceiver( 4604): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4604): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4604): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/ClockThread( 1118): stop update clock
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/ActivityManager(  911): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4639 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4604/10079)
,E/dalvikvm( 4554): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4554): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
D/WIFI_ICON( 1118): WifiActivity: 3
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/dalvikvm( 4554): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4554): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4554): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4554): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4554): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4554): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4554): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4554): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4554): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,V/SRS_Proc(  369): ParamSet string: screen_state=on
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4604/10079)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4604/10079)
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  911): updateScreenOn: false
,I/dalvikvm-heap( 4554): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,W/dalvikvm( 4554): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4554): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4554): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4554): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4554): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4554): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4554): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  911): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4652 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=4170
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 4170:com.google.android.talk/u0a111 (adj 15): empty #17
,I/dalvikvm-heap( 4554): Grow heap (frag case) to 9.973MB for 28144-byte allocation
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): acquireWL(438d5a48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(438d5a48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(42f70758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1759): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1759): onScreenOn: 1452294319100
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1759): onScreenOn: 1452294319100
,I/dalvikvm-heap( 4554): Grow heap (frag case) to 10.012MB for 39954-byte allocation
,D/PMS     (  911): releaseWL(42f70758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422734d0
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422734d0, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@41c1ab70
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  911): goingToSleep
D/PMS     (  911): acquireWL(43581758): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
D/PMS     (  911): acquireWL(43b2af78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4652): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/CheckinService( 2199): Checkin interval check for package: unspecified last checkin: 1452294270358 min interval config: 0 actual interval: 48776
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/PMS     (  911): acquireWL(4357acc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(43b2af78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4554): Grow heap (frag case) to 10.089MB for 79892-byte allocation
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4652): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/CheckinService( 2199): Checking schedule, now: 1452294319148 next: 1452294300158
,I/CheckinService( 2199): active receiver: enabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2199, uid=10029, userID:0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
W/GAV2    ( 4652): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/CheckinService( 2199): Preparing to send checkin request
,I/EventLogService( 2199): Accumulating logs since 1452294266676
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4652): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/ActivityManager(  911): Recipient 4170
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4652): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/CheckinRequestBuilder( 2199): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2199): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4554): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ba12d8 u0 ReceiverList{43ba1238 4554 com.facebook.katana/10027/u0 remote:42664e38}}
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ba12d8 u0 ReceiverList{43ba1238 4554 com.facebook.katana/10027/u0 remote:42664e38}}
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43540ee0 u0 ReceiverList{430dc0d8 4554 com.facebook.katana/10027/u0 remote:42692880}}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4652/10151)
,V/WebViewChromiumFactoryProvider( 4652): Binding Chromium to main looper Looper (main, tid 1) {41b18258}
,I/LibraryLoader( 4652): Expected native library version number "",actual native library version number ""
,I/chromium( 4652): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4652): Initializing chromium process, renderers=0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,E/AudioManagerAndroid( 4652): BLUETOOTH permission is missing!
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/PMS     (  911): acquireWL(42f92ba0): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  911): acquireWL(430f5068): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/PMS     (  911): releaseWL(430f5068): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4652): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4652): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4652): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4652): Local Branch: 
I/Adreno-EGL( 4652): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4652): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4652):                  aa63bbd948f41d15fc72f585e
,D/AlarmManager(  911): ACTION_SCREEN_OFF
,I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20675 mDataStallAlarmIntent=PendingIntent{41ed6c38: PendingIntentRecord{4254c758 android broadcastIntent}}
I/AlarmManager(  911): [AlarmQueuing] wifi connection: true
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
D/PMS     (  911): acquireWL(42a8ec40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2199/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
,I/NSApplication( 4652): Starting up...
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4652/10151)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4652/10151)
,D/PMS     (  911): acquireWL(426a0858): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  911): releaseWL(426a0858): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4099/10160)
,D/Process (  911): killProcessQuiet, pid=4300
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4099/10160)
I/ActivityManager(  911): Killing 4300:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4300
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4696 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  911): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4708 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4554): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4554): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4554): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4696): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,W/dalvikvm( 4708): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4708): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4708): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4708): install
,I/MultiDex( 4708): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/SmartSyncUtils( 4696): isEpsOn(), nState = 0
,I/MultiDex( 4708): loading existing secondary dex files
,I/MultiDex( 4708): load found 3 secondary dex files
D/PMS     (  911): acquireWL(4307c8d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4696 1000 null
,I/MultiDex( 4708): install done
D/PMS     (  911): releaseWL(4307c8d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ActivityManager(  911): Activity pause timeout for ActivityRecord{4215e328 u0 com.test.thalitest/.MainActivity t2}
,W/dalvikvm( 4708): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4708): VFY: unable to resolve instance field 36
,D/SmartSyncUtils( 4696): getMobilePolicyEnabled, result = true
,W/dalvikvm( 4708): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4708): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Process (  911): killProcessQuiet, pid=4332
,I/ActivityManager(  911): Killing 4332:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 4332
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ProviderInstaller( 4708): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  911): releaseWL(41f74e50): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,W/dalvikvm( 4708): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4708): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/ConnectivityService(  911): NetTransition Wakelock for ConnectedState released by timeout
,W/dalvikvm( 4708): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4708): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4708): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4708): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4708): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 168
,D/WifiStateMachine(  911): BroadcastRSSIForIMS, newrssi =-56 , oldRssi= -200
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): SET_SCREEN_ON:Off
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1186): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/WifiNative-wlan0(  911): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  911): NoActiveNetworkState
,D/AutoSetting( 1318): receiver - intent: android.intent.action.USER_PRESENT
,V/Tethering(  911): bSetPropertyMultiRAB:false
,D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/PMS     (  911): acquireWL(43d26278): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4604/10079)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (4534/10154)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
I/Tethering(  911): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  911): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/NetworkMonitor( 4534): type=WIFI subType= reason=null isConnected=true
I/Tethering(  911): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Tethering(  911): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
,I/Tethering(  911): Found interface wlan0
,D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.musicenhancer (3941/10053)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(43c770a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  911): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/TetherSettings( 3841): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3841): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3841): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3841): Cust_ConnectToPC   : spcsc>false
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/PMS     (  911): releaseWL(43c770a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  911): releaseWL(43d26278): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/        ( 3841): Cust_ConnectToPC   : IPT>true
D/        ( 3841): Cust_ConnectToPC   : Singel_USB>false
D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/Settings( 3841): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3841): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3841): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3841): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 3841): onReceive:android.intent.action.USER_PRESENT
,V/SRS_Proc(  369): ParamSet string: screen_state=off
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3841): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3841): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3841):  defaultType:0
D/NetworkPolicy(  911): updateScreenOn: false
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,W/ContextImpl( 4696): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/WVCdm   (  369): CdmEngine::OpenSession
I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/SmartSyncUtils( 4696): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4696): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4696): getMobilePolicyEnabled, result = true
,D/WifiService(  911): New client listening to asynchronous messages
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/NativeLibraryUtils( 4708): Install completed successfully. count=14 extracted=0
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c1ab70
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c1ab70, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c1ab70, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c1ab70
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42690b30 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42690b30 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  911): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  911): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  911): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  911): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  911): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  911): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  911): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  911): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] getTotalRam: 1873 Mb
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,D/LocationInitializer( 2199): Restart initialization of location
D/PMS     (  911): acquireWL(440d99f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(440d99f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4273a520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
E/MDM     ( 1224): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/WVCdm   (  369): PrepareKeyRequest: nonce=3367393311
D/AuthorizationBluetoothService( 1381): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1381): Proximity feature is not enabled.
D/PMS     (  911): releaseWL(4273a520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1759): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1759): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1759): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1759): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1759): onScreenOff
W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
D/PMS     (  911): acquireWL(422842a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(422842a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2401/10021)
D/AutoSetting( 1318): service - mHandler: cancel location update
D/AutoSetting( 1318): service -           changes count: 0
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/AutoSetting( 1318): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4604): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4604): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
,D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1318): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1318): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1318): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4652/10151)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4099/10160)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4099/10160)
,D/PMS     (  911): acquireWL(424d9078): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2199): Checkin interval check for package: unspecified last checkin: 1452294270358 min interval config: 0 actual interval: 49692
D/PMS     (  911): releaseWL(424d9078): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4099): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2199, uid=10029, userID:0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,W/Settings( 4708): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4708): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4708): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4708):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  369): PrepareKeyRequest: nonce=1181299601
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  911): releaseWL(42a8ec40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wla,n0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (4708/10029)
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4708): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4708): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4708):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4708): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4708): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4708):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2199): Classify the device as Phone.
,D/libc    ( 2199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2199): [NET] getaddrinfo-,err=8
,D/libc    ( 2199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2199): [NET] getaddrinfo-, 1
,D/libc    ( 2199): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =6abe +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 128
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2199): [NET] getaddrinfo_proxy-, success
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=9 entropy=0
D/wpa_supplicant( 1186): Add randomness: count=10 entropy=1
D/wpa_supplicant( 1186): Add randomness: count=11 entropy=2
D/wpa_supplicant( 1186): Add randomness: count=12 entropy=3
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1186): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 ,- cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=13 entropy=4
D/wpa_supplicant( 1186): Add randomness: count=14 entropy=5
D/wpa_supplicant( 1186): Add randomness: count=15 entropy=6
D/wpa_supplicant( 1186): Add randomness: count=16 entropy=7
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
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000108117850
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000108117879
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=2
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-55
I/wpa_supplicant( 1186): tsf=0000000108117869
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-82
I/wpa_supplicant( 1186): tsf=0000000108117887
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108117850, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  911): InactiveState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4407efd8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4407efd8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4407efd8 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 108117879, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 108117869, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 108117887, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
D/libc    ( 2199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2199): [NET] getaddrinfo-,err=8
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/libc    ( 2199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2199): [NET] getaddrinfo-,err=8
,D/libc    ( 2199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2199): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2199): Sending checkin request (12193 bytes)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,W/fb4a(:<default>):UserScope( 4554): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4554): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=19 [21][4][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =a4fe +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,E/fb4a(:<default>):LocalFbBroadcastManager( 4554): Called registerBroadcastReceiver twice.
,I/CheckinRequestBuilder( 2199): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2199): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  911): Find DNS Address www.htc.com/104.81.130.175
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4554/10027)
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2199/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [3][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,I/CheckinRequestBuilder( 2199): Classify the device as Phone.
,I/CheckinTask( 2199): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2199): Checking schedule, now: 1452294321961 next: 1452817258956
,I/CheckinService( 2199): active receiver: disabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2199, uid=10029, userID:0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,I/CheckinService( 2199): Checking schedule, now: 1452294321986 next: 1452817258956
,I/CheckinService( 2199): active receiver: disabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2199, uid=10029, userID:0
,D/CheckinService( 2199): Recording last checkin time for package unspecified as 1452294321991
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(4357acc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2199/10029)
,D/PMS     (  911): acquireWL(43071218): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1381): [NET] getaddrinfo-,err=8
D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1381): [NET] getaddrinfo-, 1
,D/libc    ( 1381): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =873b +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
D/PMS     (  911): acquireWL(42661438): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4534 10154 null
,W/ContextImpl( 4534): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 4534): Conditions not met for autocaching.
,I/MusicLeanback( 4534): Stop autocaching.
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4534, uid=10154, userID:0
,D/PMS     (  911): releaseWL(42661438): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
W/ContextImpl( 4534): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 99
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1381): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1381): [NET] getaddrinfo-,err=8
,D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1381): [NET] getaddrinfo-,err=8
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/PMS     (  911): releaseWL(42f92ba0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  911): acquireWL(437d08d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/PMS     (  911): releaseWL(43071218): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1381/10029)
,D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
,D/PMS     (  911): releaseWL(437d08d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43ba8d20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1381/10029)
,D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1381/10029)
,D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(43ba8d20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=9 [11][1][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ActivityManager(  911): Sleep timeout!  Sleeping now.
,D/PMS     (  911): releaseWL(43581758): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/GAV2    ( 4652): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4483): Test app app.js loaded
I/jxcore-log( 4483): 
,I/Choreographer( 4483): Skipped 522 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4483): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4483): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b201e0 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4483): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Process (  911): killProcessQuiet, pid=4355
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4355:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4355
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4371
,I/ActivityManager(  911): Killing 4371:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 4371
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  911): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4774 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsUpdated
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  911):   Scheme: "smsto"
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/dalvikvm( 4774): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4774): VFY: unable to resolve instance field 36
,W/dalvikvm( 4774): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Babel   ( 4774): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4774): MmsConfig.loadMmsSettings
,V/JNIHelp ( 4774): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  911): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4797 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4774, uid=10111, userID:0
,W/Settings( 4774): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4774, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4774, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4774, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4774, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4774, uid=10111, userID:0
,D/MessageFrequencyProvider( 4797): onCreate
D/PMS     (  911): acquireWL(42684d20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4774 10111 null
,D/MmsCustomizationProvider( 4797): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4797): GetPrviateResource
,V/GetPrviateResource( 4797): GetPrviateResource
,I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
,D/MmsCustomizationProvider( 4797): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/ActivityManager(  911): Resuming delayed broadcast
,I/Babel   ( 4774): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4774): MmsConfig.loadFromDatabase
,I/IcingCorporaProvider( 2855): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,E/Babel   ( 4774): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4774): MmsConfig.loadFromResources
,D/PMS     (  911): acquireWL(43514f40): PARTIAL_WAKE_LOCK  Icing 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
E/Babel   ( 4774): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4774): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  911): releaseWL(42684d20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  911): killProcessQuiet, pid=4319
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4319:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4319
,I/ProviderInstaller( 4774): Installed default security provider GmsCore_OpenSSL
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/PackageManager(  911): Unable to load service info ResolveInfo{42664ac8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
,D/MessageCustFlag( 4797): sense_version=6.0
,D/BTAccessoryUtil( 4797): createReceiver
,D/BTAccessoryUtil( 4797): registerReceiver return intent = null
D/MessageCustFlag( 4797): sku_id=99
,W/SystemReader( 4797): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4797): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4797): networkCode: 
,D/MessageCustFlag( 4797): sku_id=99
D/MmsConfig( 4797): SIE smsPri: null
,D/MmsConfig( 4797): networkCode: 
,D/HtcTelephonyCapability( 4797): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4797): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4797): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4797): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  911): releaseWL(43514f40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(42fb6cd0): PARTIAL_WAKE_LOCK  Icing 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/dalvikvm-heap( 4099): Grow heap (frag case) to 15.203MB for 1821008-byte allocation
D/PMS     (  911): acquireWL(44239b30): PARTIAL_WAKE_LOCK  AsyncService 0x1 4099 10160 null
,D/PMS     (  911): releaseWL(42fb6cd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4099): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
D/PMS     (  911): acquireWL(4320aaf8): PARTIAL_WAKE_LOCK  Icing 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(44239b30): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  911): releaseWL(4320aaf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  911): acquireWL(43658c18): PARTIAL_WAKE_LOCK  Icing 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  911): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  911): releaseWL(43658c18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(440cf320): PARTIAL_WAKE_LOCK  Icing 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  911): releaseWL(440cf320): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(4322ecc8): PARTIAL_WAKE_LOCK  Icing 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2199): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2199): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2199): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,I/IcingCorporaProvider( 2855): UpdateCorporaTask done [took 376 ms] updated apps [took 376 ms] 
D/RemoteDisplayProvider(  911): start
I/ActivityManager(  911): Resuming delayed broadcast
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  911): applying state to connected service
,D/PMS     (  911): acquireWL(440ca870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(440ca870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  911): applying state to connected service
D/PMS     (  911): acquireWL(4392fef8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(4392fef8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43d26e60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43d26e60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41ba6f10 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,I/Icing   ( 2199): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Process (  911): killProcessQuiet, pid=3941
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3941:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3941
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2199): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  911): releaseWL(4322ecc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41ba6f10 -
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,D/Messaging( 4797): mNeedToUpdateDate2 start
,D/MmsConfig( 4797): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4797): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4797): 
D/MmsAsyncWorkHandler( 4797): HM tk = 20001
,D/ReportIndicatorCache( 4797): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4797): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b1a4e8
,I/Messaging( 4797): mccmnc> 
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/DraftCache( 4797): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4797): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1241):  phoneType = -1
D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4797): networkCode: 
,D/Messaging( 4797): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 4797): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4797): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4797): createReceiver
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MessageCustFlag( 4797): sense_version=6.0
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Jerry   ( 4797): start to preload cursor >>>>>>>
,D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1241): Update uri=content://mms, match=0
,V/MmsProvider( 1241): selection=st=129 AND m_type!=134
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4797): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4797): TransactionService is going to be woken up.
,D/Messaging( 4797): mNeedToUpdateDate2: false
,V/TransactionService( 4797): 1-Creating TransactionService
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1241): sku_id=99
,V/TransactionService( 4797): onStartCommand: 1
D/MmsSystemEventReceiver( 4797): unRegisterForConnectionStateChanges
V/TransactionService( 4797): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4797): Loading previous transactions.
,D/DraftCache( 4797): [DraftCache/478] rebuildCache
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): device_type: 1
,D/TransactionService( 4797): Force set service start id to 1
V/TransactionService( 4797): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4797): unRegisterForConnectionStateChanges
,D/TransactionService( 4797): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4797): Destroying TransactionService
,V/TransactionService( 4797): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4797): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/Messaging( 4797): ViewCache CreatePreload
,D/Messaging( 4797): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/Jerry   ( 1241): URI_DRAFT
,D/Cust_MMSMS( 4797): _has_set_default_values_2=true
,D/DraftCache( 4797): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4797): [DraftCache/478] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4797): 
D/MmsAsyncWorkHandler( 4797): HM tk = 20002
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): sku_id=99
,D/MsgPreferenceUtils( 4797): def_index: 0
,D/MsgPreferenceUtils( 4797): globalIndex = 1
D/MsgPreferenceUtils( 4797): phone state: true
D/MsgPreferenceUtils( 4797): sd state: false
,D/MsgPreferenceUtils( 4797): vIndex = 0
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1241): sku_id=99
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{42f35650 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4774): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/PMS     (  911): acquireWL(44246598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  911): sending alarm PendingIntent{43652288: PendingIntentRecord{4239a628 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123124, Int=0
D/PMS     (  911): releaseWL(44246598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(441e14a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  911): acquireWL(441a74b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(441a74b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(441e14a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(441530d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(441530d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44147650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): acquireWL(441068c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(440e5f28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1224): Vacuum at: now=1452294336302 tag=VacuumService
D/PMS     (  911): releaseWL(44147650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(441068c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43d35cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(43d35cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43c2acc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(440e5f28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868,
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(43c2acc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4267fdf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(4267fdf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(424b8140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(424b8140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41b4c488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): acquireWL(41dab290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(41dab290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(424703b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(41b4c488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42751678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(42751678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype for one-off execution 6119 seconds from now (1452294336780)
,D/GetConfigurationSnapshotOperation( 1224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1186): Change stage from stage3 to stage0
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1186): Change stage from stage0 to stage3
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/PhenotypeFlagCommitter( 1224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
,D/libc    ( 1224): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =280 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=17 entropy=8
D/wpa_supplicant( 1186): Add randomness: count=18 entropy=9
D/wpa_supplicant( 1186): Add randomness: count=19 entropy=10
D/wpa_supplicant( 1186): Add randomness: count=20 entropy=11
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1186): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 ,level=-55
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=21 entropy=12
D/wpa_supplicant( 1186): Add randomness: count=22 entropy=13
D/wpa_supplicant( 1186): Add randomness: count=23 entropy=14
D/wpa_supplicant( 1186): Add randomness: count=24 entropy=15
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000108117850
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-55
I/wpa_supplicant( 1186): tsf=0000000125192473
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=2
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-55
I/wpa_supplicant( 1186): tsf=0000000125192461
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-82
I/wpa_supplicant( 1186): tsf=0000000125192483
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108117850, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 125192473, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 125192461, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 125192483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList,
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  911): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  911): == (4) end of scan result ==,
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 224
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=26 [23][6][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(424703b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(423c0730): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(423c0730): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4268e7e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(4268e7e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42f08488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
,D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(42f08488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(43533c28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{426ff470: PendingIntentRecord{425671e8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137005, Int=0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1381/10029)
,D/PMS     (  911): releaseWL(43533c28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1318): service - mHandler: update timezone
,D/AutoSetting( 1318): service - handleMessage() stop self
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1318): service - handleMessage() quit looper
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1511): service - onCreate()
,D/AutoSetting( 1318): service - onDestroy() END
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: processTimeZoneID
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1511): service - mHandler: update timezone
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1511): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1511): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41f4cee8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 8 2 11
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  911): acquireWL(42689780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41b64df0: PendingIntentRecord{423e15d0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142185, Int=0
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(43a4ba68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(42689780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =9d3e +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=25 entropy=16
D/wpa_supplicant( 1186): Add randomness: count=26 entropy=17
D/wpa_supplicant( 1186): Add randomness: count=27 entropy=18
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
,I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=28 entropy=19
D/wpa_supplicant( 1186): Add randomness: count=29 entropy=20
D/wpa_supplicant( 1186): Add randomness: count=30 entropy=21
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000142463865
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000142463891
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=2
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-55
I/wpa_supplicant( 1186): tsf=0000000125192461
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000125192483
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ####
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 142463865, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 142463891, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 125192461, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 125192483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=243
D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo_proxy-, success
,I/global  (  911): call createSocket() return a new socket.
D/libc    (  911): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  911): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  911): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  911): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  911):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  911): killProcessQuiet, pid=4405
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4405:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4405
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(440957f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41b16d88: PendingIntentRecord{41cef258 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=147023, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(440957f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): releaseWL(43a4ba68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{434f43d0 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=31 entropy=22
D/wpa_supplicant( 1186): Add randomness: count=32 entropy=23
D/wpa_supplicant( 1186): Add randomness: count=33 entropy=24
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1186): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
,D/wpa_supplicant( 1186): Add randomness: count=34 entropy=25
D/wpa_supplicant( 1186): Add randomness: count=35 entropy=26
D/wpa_supplicant( 1186): Add randomness: count=36 entropy=27
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1186): reply (376) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000142463865
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000159734154
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000159734166
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 142463865, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 159734154, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 159734166, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 3 to mScanResults
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==,
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(43981360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(43981360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4420
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4420:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4420
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=37 entropy=28
D/wpa_supplicant( 1186): Add randomness: count=38 entropy=29
D/wpa_supplicant( 1186): Add randomness: count=39 entropy=30
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=40 entropy=31
D/wpa_supplicant( 1186): Add randomness: count=41 entropy=32
D/wpa_supplicant( 1186): Add randomness: count=42 entropy=33
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (376) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000176993665
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000176993691
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000176993703
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ####
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 176993665, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 176993691, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 176993703, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  911): acquireWL(4351f8c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/PMS     (  911): releaseWL(4351f8c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=43 entropy=34
D/wpa_supplicant( 1186): Add randomness: count=44 entropy=35
D/wpa_supplicant( 1186): Add randomness: count=45 entropy=36
D/wpa_supplicant( 1186): Add randomness: count=46 entropy=37
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1186): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=47 entropy=38
D/wpa_supplicant( 1186): Add randomness: count=48 entropy=39
D/wpa_supplicant( 1186): Add randomness: count=49 entropy=40
D/wpa_supplicant( 1186): Add randomness: count=50 entropy=41
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000194254067
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
,I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000194254094
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000194254117
,I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=4
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000194254105
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ####
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 194254067, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 194254094, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 194254117, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 194254105, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  911): == (4) end of scan result ==,
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WirelessDisplayService(  911): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(43aeec28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41b16d88: PendingIntentRecord{41cef258 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=207023, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43aeec28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=51 entropy=42
D/wpa_supplicant( 1186): Add randomness: count=52 entropy=43
D/wpa_supplicant( 1186): Add randomness: count=53 entropy=44
D/wpa_supplicant( 1186): Add randomness: count=54 entropy=45
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1186): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=55 entropy=46
D/wpa_supplicant( 1186): Add randomness: count=56 entropy=47
D/wpa_supplicant( 1186): Add randomness: count=57 entropy=48
D/wpa_supplicant( 1186): Add randomness: count=58 entropy=49
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000211513878
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000211513904,
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000211513927
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=4
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000211513916
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ####
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 211513878, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 211513904, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 211513927, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 211513916, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(42605718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,D/PMS     (  911): releaseWL(42605718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43b891d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10027}
,V/AlarmManager(  911): sending alarm PendingIntent{4354b558: PendingIntentRecord{441d4818 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226360, Int=0
,I/ActivityManager(  911): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4884 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  911): sending alarm PendingIntent{4266b1f0: PendingIntentRecord{42406790 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452294425050, Int=10800000
,V/AlarmManager(  911): sending alarm PendingIntent{441376e8: PendingIntentRecord{43c9a980 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=226372, Int=120000,
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/PMS     (  911): releaseWL(43b891d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.aurora (4884/10049)
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025053
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025115
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025118
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026541
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026568
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029438
,D/Process (  911): killProcessQuiet, pid=4063
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4063:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4063
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=59 entropy=50
D/wpa_supplicant( 1186): Add randomness: count=60 entropy=51
D/wpa_supplicant( 1186): Add randomness: count=61 entropy=52
D/wpa_supplicant( 1186): Add randomness: count=62 entropy=53
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1186): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=63 entropy=54
D/wpa_supplicant( 1186): Add randomness: count=64 entropy=55
D/wpa_supplicant( 1186): Add randomness: count=65 entropy=56
D/wpa_supplicant( 1186): Add randomness: count=66 entropy=57
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000228853696
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000228853722
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000228853743
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=4
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000228853733
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ####
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 228853696, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 228853722, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 228853743, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 228853733, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiStateMachine(  911): == begin of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=67 entropy=58
D/wpa_supplicant( 1186): Add randomness: count=68 entropy=59
D/wpa_supplicant( 1186): Add randomness: count=69 entropy=60
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=70 entropy=61
D/wpa_supplicant( 1186): Add randomness: count=71 entropy=62
D/wpa_supplicant( 1186): Add randomness: count=72 entropy=63
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000228853696
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000246163351
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000246163362
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=4
,I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000228853733
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 228853696, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 246163351, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 246163362, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 228853733, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WifiStateMachine(  911): add 4 to mScanResults
V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(437d37f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  911): releaseWL(437d37f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=73 entropy=64
D/wpa_supplicant( 1186): Add randomness: count=74 entropy=65
D/wpa_supplicant( 1186): Add randomness: count=75 entropy=66
D/wpa_supplicant( 1186): Add randomness: count=76 entropy=67
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1186): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling,
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
,I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=77 entropy=68
D/wpa_supplicant( 1186): Add randomness: count=78 entropy=69
,D/wpa_supplicant( 1186): Add randomness: count=79 entropy=70
D/wpa_supplicant( 1186): Add randomness: count=80 entropy=71
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000263414224
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000263414250
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000263414272
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=4
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000263414261
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ####
,D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 263414224, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 263414250, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 263414272, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 263414261, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults,
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0,
D/WifiStateMachine(  911): == begin of scan result ==
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): == (4) end of scan result ==,
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(43451438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000},
,V/AlarmManager(  911): sending alarm PendingIntent{41b16d88: PendingIntentRecord{41cef258 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=267022, Int=0,
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43451438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=81 entropy=72
D/wpa_supplicant( 1186): Add randomness: count=82 entropy=73
D/wpa_supplicant( 1186): Add randomness: count=83 entropy=74
D/wpa_supplicant( 1186): Add randomness: count=84 entropy=75
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1186): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=85 entropy=76
D/wpa_supplicant( 1186): Add randomness: count=86 entropy=77
D/wpa_supplicant( 1186): Add randomness: count=87 entropy=78
D/wpa_supplicant( 1186): Add randomness: count=88 entropy=79
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
,I/wpa_supplicant( 1186): tsf=0000000280663713
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000280663739
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000280663760
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=4
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000280663750
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ####
,D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 280663713, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 280663739, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 280663760, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 280663750, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/PMS     (  911): acquireWL(43a91098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
I/BatteryService(  911): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(43a91098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
,D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=89 entropy=80
D/wpa_supplicant( 1186): Add randomness: count=90 entropy=81
D/wpa_supplicant( 1186): Add randomness: count=91 entropy=82
D/wpa_supplicant( 1186): Add randomness: count=92 entropy=83
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 9
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 0
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1186): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1186): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1186): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1186): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1186): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=93 entropy=84
D/wpa_supplicant( 1186): Add randomness: count=94 entropy=85
D/wpa_supplicant( 1186): Add randomness: count=95 entropy=86
D/wpa_supplicant( 1186): Add randomness: count=96 entropy=87
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): clear disabled list - type=1
I/wpa_supplicant( 1186): No suitable network found
W/wpa_supplicant( 1186): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1186): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1186): reply (489) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000297904085
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000297904112
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=3
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-81
I/wpa_supplicant( 1186): tsf=0000000297904137
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=4
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-56
I/wpa_supplicant( 1186): tsf=0000000297904126
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiP2pService(  911): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 297904085, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 297904112, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 297904137, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 297904126, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/jxcore-log( 4483): --= Surplus to requirements =--
I/jxcore-log( 4483): 
I/jxcore-log( 4483): ****TEST TOOK:  ms ****
I/jxcore-log( 4483): 
,I/jxcore-log( 4483): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4483): 
,E/cutils-trace( 4907): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4907): ====startRecUseTime====
D/htc.customization.log.level( 4907):  is 
,W/CustomizationLogLevel( 4907): Level value is invalid, use default level 2
,D/CustomizationManager( 4907):  Read ACC file spent 0.089 (s)
D/CIDMapFileReader( 4907): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4907): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4907): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4907): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4907): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4907): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4907): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4907): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4907): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4907): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4907): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4907): Parsing tag category name = system
I/CustomizationCIDLoader( 4907): Parsing tag category name = application
I/CustomizationCIDLoader( 4907): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 4907): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4907): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 4907): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4907): Parsing tag category name = Settings
D/CustomizationManager( 4907):  Read CID file spent 0.131 (s)
,D/CustomizationManager( 4907):  All configurations done spent 0.131 (s),
,W/HtcNativeFlag( 4907): Fail to get flag string for type 'customer', use default value,
W/HtcNativeFlag( 4907): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4907): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4907): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4907, uid=2000 user=0
,I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  911): killProcessQuiet, pid=4483
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  911): Killing 4483:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  911): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  911):   Force finishing activity ActivityRecord{4215e328 u0 com.test.thalitest/.MainActivity t2}
,E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1210): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  911): Got RemoteException sending setActive(false) notification to pid 4483 uid 10389
,W/PackageSettings(  911): Skipping PackageSetting{4229e2b0 com.example.hello/10397} due to missing metadata
,I/WindowState(  911): WIN DEATH: Window{424cd7c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,D/WifiService(  911): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  911): acquireWL(43657e38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  911): releaseWL(43657e38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
D/VoicemailCleanupService( 1286): Cleaning up data for package: com.test.thalitest
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/SQLiteConnectionPool( 2199): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsRemoved
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
,D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :,
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/IcingCorporaProvider( 2855): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4923 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  911): acquireWL(43291e30): PARTIAL_WAKE_LOCK  Icing 0x1 2199 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2855): UpdateCorporaTask done [took 232 ms] updated apps [took 232 ms] 
,W/PackageManager(  911): Unable to load service info ResolveInfo{41e2fdd8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4923): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4923): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4923): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4923): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4923): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4923): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4923): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4923): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4923): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4923): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4923): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4923): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4923): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4923): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4923): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4923): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4923): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4923): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4923): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4923): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4923): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4923): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4923): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4923): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4923): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 4923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4923): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4923): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4923): ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4923): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4923): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4923): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4923): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4923): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4923): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4923): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4923): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4923): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4923): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4923): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4923): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4923): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4923): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4923): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4923): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4923): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4923): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4923): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4923): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4923): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4923): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4923): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4923): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4923): Opened ClientFlag.db in read-only mode,
,E/SQLiteDatabase( 4923): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4923): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4923): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4923): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4923): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4923): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4923): threadid=11: thread exiting with uncaught exception (group=0x416e3e30)
,E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4923): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4923): Process: com.google.android.apps.docs, PID: 4923
E/AndroidRuntime( 4923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4923): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4923): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4923): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4923): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4923): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
,E/SQLiteDatabase( 4923): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4923): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4923): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4923): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4923): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4923): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4923): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4923): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4923): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4923): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4923): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4923): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4923): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4923): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4923): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240),
E/SQLiteOpenHelper( 4923): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4923): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4923): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4923): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,E/SQLiteOpenHelper( 4923): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4923): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4923): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222),
E/SQLiteOpenHelper( 4923): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4923): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4923): ,	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4923): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4923): 	at android.os.Looper.loop(Looper.java:157)
,E/SQLiteOpenHelper( 4923): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4923): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4923): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4923): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4923): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712),
E/SQLiteOpenHelper( 4923): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4923): Opened ClientFlag.db in read-only mode
,I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4941 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4923): killProcess, pid=4923
D/Process ( 4923): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  911): Recipient 4923
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  911): start
,D/Process (  911): killProcessQuiet, pid=4454
,I/ActivityManager(  911): Killing 4454:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4923) has died.
,I/ActivityManager(  911): Recipient 4454
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AtomicFile(  911): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  911): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/ContextImpl( 4941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4941): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4941): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4941): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4941): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4941): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4941): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4941): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4941): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4941): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4941): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4941): threadid=10: thread exiting with uncaught exception (group=0x416e3e30)
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4955 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/AndroidRuntime( 4941): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4941): Process: com.android.keychain, PID: 4941
E/AndroidRuntime( 4941): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4941): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4941): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4941): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4941): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4941): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4941): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4941): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4941): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  911): App crashed! Process: com.android.keychain
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
,E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452294512974.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
D/Process ( 4941): killProcess, pid=4941
D/Process ( 4941): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  911): Recipient 4941
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/ActivityManager(  911): Process com.android.keychain (pid 4941) has died.
,W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/AppTag  ( 4955): getInstance(Context context)
,D/AppTag  ( 4955): getInstance(Context context)
,D/AppTag  ( 4955): onCreate()
,D/PMS     (  911): acquireWL(426026b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4099 10160 null
,D/PMS     (  911): releaseWL(426026b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4125): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PackageBroadcastService( 2199): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2199): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2199): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2199): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2199): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2199): Module APK com.google.android.play.games already loaded
I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2199): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2199): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e4d29c0
,W/dalvikvm( 2199): threadid=48: thread exiting with uncaught exception (group=0x416e3e30)
,E/SQLiteLog( 2199): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2199): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x61823408
,I/LocationSettingsChecker( 2199): Removing dialog suppression flag for package com.test.thalitest
E/AndroidRuntime( 2199): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2199): Process: com.google.android.gms, PID: 2199
E/AndroidRuntime( 2199): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2199): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2199): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2199): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2199): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2199): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2199): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2199): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2199): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2199): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2199): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2199): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2199): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2199): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2199): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2199): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2199): 	at java.lang.Thread.run(Thread.java:864)
,E/DriveAsyncService( 2199): disk I/O error (code 3850)
E/DriveAsyncService( 2199): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2199): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2199): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2199): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2199): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2199): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2199): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2199): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2199): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2199): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2199): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2199): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2199): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2199): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2199): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2199): 	at java.lang.Thread.run(Thread.java:864)
,E/ActivityManager(  911): App crashed! Process: com.google.android.gms
,E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
D/Process ( 2199): killProcess, pid=2199
D/Process ( 2199): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/ActivityManager(  911): Recipient 2199
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Process com.google.android.gms (pid 2199) has died.
D/WifiService(  911): Client connection lost with reason: 4
,D/PMS     (  911): handleWLDeath(43291e30): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 21000ms
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
,I/ActivityManager(  911): Resuming delayed broadcast
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20996ms
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30995ms
,E/SQLiteLog( 1381): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1381): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x6412a6e0
,W/dalvikvm( 1381): threadid=1: thread exiting with uncaught exception (group=0x416e3e30)
,E/AndroidRuntime( 1381): FATAL EXCEPTION: main
E/AndroidRuntime( 1381): Process: com.google.process.gapps, PID: 1381
E/AndroidRuntime( 1381): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1381): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1381): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1381): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1381): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1381): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1381): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1381): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1381): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1381): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1381): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1381): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1381): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1381): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1381): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1381): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1381): 	... 10 more
,E/ActivityManager(  911): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
,I/ActivityManager(  911): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4988 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1381): killProcess, pid=1381
D/Process ( 1381): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/DeviceManagement( 4988): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4988 dbg=false s=true
,I/DeviceManagement( 4988): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4988): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4988): WorkflowService: Starting workflow service
,I/ActivityManager(  911): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/DeviceManagement( 4988): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b44e08] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4988): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4988): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4988): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4988): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4988): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4988): SessionStateController: Checking invariants...
,I/ActivityManager(  911): Recipient 1381
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.process.gapps (pid 1381) has died.
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 40813ms
,D/WifiService(  911): Client connection lost with reason: 4
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41ba6f10 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,E/SQLiteDatabase( 4988): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4988): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4988): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4988): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4988): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4988): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4988): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4988): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4988): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4988): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4988): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4988): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4988): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4988): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4988): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4988): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4988): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4988): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 4988): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4988): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4988): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4988): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4988): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4988): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4988): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4988): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4988): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4988): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4988): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4988): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b44e08]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4988): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4988): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4988): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4988): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4988): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4988): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4988): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4988): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4988): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  911): Resuming delayed broadcast
I/DeviceManagement( 4988): WorkflowService: Stopping workflow service
I/ActivityManager(  911): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5004 uid=10099 gids={50099, 3003, 5012}
D/Process (  911): killProcessQuiet, pid=4696
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4696:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/WifiService(  911): Client connection lost with reason: 4
I/ActivityManager(  911): Recipient 4696
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Documents( 5004): Loading roots for com.android.providers.downloads.documents
,D/Documents( 5004): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 5004): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5004): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5004): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5004): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5004): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5004): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5004): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5004): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5004): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5004): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5004): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5004): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5004): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5004): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5004): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5004): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5004): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5004): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5004): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5004): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5004): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 5004): threadid=1: thread exiting with uncaught exception (group=0x416e3e30)
E/AndroidRuntime( 5004): FATAL EXCEPTION: main
E/AndroidRuntime( 5004): Process: com.android.documentsui, PID: 5004
E/AndroidRuntime( 5004): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5004): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5004): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5004): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5004): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5004): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5004): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5004): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5004): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5004): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5004): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5004): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5004): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5004): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5004): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5004): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5004): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5004): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5004): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5004): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5004): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5004): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5004): 	... 10 more
,I/ActivityManager(  911): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5017 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  911): killProcessQuiet, pid=4604
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/ActivityManager(  911): App crashed! Process: com.android.documentsui
I/ActivityManager(  911): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5029 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  911): Killing 4604:com.google.android.setupwizard/u0a79 (adj 15): empty #17
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process (  911): killProcessQuiet, pid=4639
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  911): Killing 4639:com.android.chrome/u0a96 (adj 15): empty #17
I/ActivityManager(  911): Recipient 4604
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process ( 5004): killProcess, pid=5004
,D/Process ( 5004): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452294513735.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0

```
