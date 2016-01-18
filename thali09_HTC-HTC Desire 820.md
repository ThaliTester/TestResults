#### Test 56151093f6e24ff_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  910): setLight #0: color=#3e
V/LightsService(  910): setLight #0: color=#3b
V/LightsService(  910): setLight #0: color=#31
V/LightsService(  910): setLight #0: color=#2d
V/LightsService(  910): setLight #0: color=#23
V/LightsService(  910): setLight #0: color=#20
V/LightsService(  910): setLight #0: color=#19
V/LightsService(  910): setLight #0: color=#14
,--------- beginning of /dev/log/main
E/cutils-trace( 4533): Error opening trace file: No such file or directory (2)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/CustomizationManager( 4533): ====startRecUseTime====
D/htc.customization.log.level( 4533):  is 
W/CustomizationLogLevel( 4533): Level value is invalid, use default level 2
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/CustomizationManager( 4533):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4533): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4533): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4533): Parsing tag category name = system
I/CustomizationCIDLoader( 4533): Parsing tag category name = application
I/CustomizationCIDLoader( 4533): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4533): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4533): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4533): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4533): Parsing tag category name = Settings
D/CustomizationManager( 4533):  Read CID file spent 0.111 (s)
D/CustomizationManager( 4533):  All configurations done spent 0.111 (s)
W/HtcNativeFlag( 4533): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4533): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4533): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4533): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4533
D/PMS     (  910): acquireHCC(43152478): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(4279bee8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x69c4bc50 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1115516224
D/PMS     (  910): acquireWL(427143b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f5d478
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4544 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4544): Copying FileAsset 0x5c7ca648 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4544): Binding Chromium to main looper Looper (main, tid 1) {41e10458}
I/LibraryLoader( 4544): Expected native library version number "",actual native library version number ""
I/chromium( 4544): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4544): Initializing chromium process, renderers=0
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427df728:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  910): acquireWL(42789618): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  910): acquireWL(4268b9a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  910): releaseWL(42789618): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4544): 1105354360: getState(). Returning 12
I/Adreno-EGL( 4544): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4544): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4544): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4544): Local Branch: 
I/Adreno-EGL( 4544): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4544): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4544):                  aa63bbd948f41d15fc72f585e
W/chromium( 4544): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4544): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4544): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4544): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4544): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4544): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4544): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4544): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4544): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4544): CordovaWebView is running on device made by: HTC
,W/AwContents( 4544): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  910): Disable input method client, pid=1271
,W/ResourceType( 4544): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4544): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41e57528, mServedView=org.apache.cordova.engine.SystemWebView{41e1d190 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  910): Enable input method client, pid=4544
W/AwContents( 4544): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +298ms
,D/PMS     (  910): releaseWL(427143b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4544): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4544): JniHelper::setJavaVM(0x419cd010), pthread_self() = 1664232752
,D/JX-Cordova( 4544): jxcore cordova android initializing
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 12.000MB for 42652-byte allocation
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 12.078MB for 95956-byte allocation
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 12.158MB for 143930-byte allocation
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 12.272MB for 215890-byte allocation
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 12.448MB for 323830-byte allocation
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 12.719MB for 485740-byte allocation
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 13.732MB for 1092904-byte allocation
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 14.638MB for 1639352-byte allocation
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 15.946MB for 2459024-byte allocation
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
D/PMS     (  910): releaseHCC(43152478): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(4279bee8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4544): Grow heap (frag case) to 18.070MB for 3688532-byte allocation
,W/jxcore-log( 4544): Initializing JXcore engine
,W/jxcore-log( 4544): JXcore engine is ready
,W/jxcore-log( 4544): Starting JXcore engine
,I/SensorManager(  910): mEventCount = 1200
,W/jxcore-log( 4544): Platform android
W/jxcore-log( 4544): 
,W/jxcore-log( 4544): Process ARCH arm
W/jxcore-log( 4544): 
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  910): releaseWL(4268b9a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4544): JXcore Cordova bridge is ready!
I/jxcore-log( 4544): 
,W/jxcore-log( 4544): JXcore engine is started
,I/chromium( 4544): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4544): Toggling radios to true
I/jxcore-log( 4544): 
,D/BluetoothAdapter( 4544): enable(): BT is already enabled..!
,D/WifiManager( 4544): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  910): New client listening to asynchronous messages
D/WifiService(  910): setWifiEnabled: true pid=4544, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1269
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump
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
D/WifiManager( 4544): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
D/WifiManager( 4544): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): TDLS: Tear down peers
I/wpa_supplicant( 1184): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4544): Radios toggled
I/jxcore-log( 4544): 
I/jxcore-log( 4544): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4544): 
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1184): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1184): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1184): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb73c7bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
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
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
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
D/wpa_supplicant( 1184): Wi,reless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1184): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  910):    returned true
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
,D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412,
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  910):    returned true
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(429d2520): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0(  910): doBoolean: RECONNECT
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20765 mDataStallAlarmIntent=PendingIntent{4410b938: PendingIntentRecord{42613c90 android broadcastIntent}}
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): Fast associate: Old scan results
I/wpa_supplicant( 1184): wpa_supplicant_scan enter
I/wpa_supplicant( 1184): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1184): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1184): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1184): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1184): nl80211: Event message available
,D/wpa_supplicant( 1184): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WISPrService( 3850): >>>>>WISPrService start isConnected = false<<<<<
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/UsbnetStateTracker(  910): isAvailable+-
D/WifiNative-wlan0(  910):    returned true
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect(),
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 3850): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  910): New client listening to asynchronous messages
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
V/NativeCrypto( 1359): Read error: ssl=0x6607b5e0: I/O error during system call, Connection timed out
,D/WISPrService( 3850): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  362): [NET] entry_id:4   entry:0xb81e3cd8  removed 
D/libc    (  362): [NET] entry_id:8   entry:0xb81df1b8  removed 
D/libc    (  362): [NET] entry_id:3   entry:0xb81e3db8  removed 
D/libc    (  362): [NET] entry_id:6   entry:0xb81df2e8  removed 
D/libc    (  362): [NET] entry_id:7   entry:0xb81daaf8  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb81e3f70  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb81dac20  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb81df458  removed 
D/libc    (  362): [NET] entry_id:9   entry:0xb81da9d0  removed 
,D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x6607b5e0: I/O error during system call, Broken pipe
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/PMS     (  910): acquireWL(434eac10): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  910): acquireWL(42fcf1f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WISPrService( 3850): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
I//system/bin/ip(  362): RTNETLINK answers: No such process
,D/WifiNative-wlan0(  910): doBoolean: SCAN
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
I/logwrapper(  362): /system/bin/ip terminated by exit(2)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  910):    returned false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/BatSI   (  910): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  910): releaseWL(434eac10): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  910): releaseWL(42fcf1f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4595 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42947b00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(42947b00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4394/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4394/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,I/MusicStore( 4595): Database version: 95
,W/ContextImpl( 4595): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4595): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4595): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4595): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4595): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4595, uid=10154, userID:0
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/MediaRouterService(  910): Client com.google.android.music (pid 4595): Registered
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
I/MediaRouter( 4595): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4595/10154)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1886/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4615 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4595): getSelectedRoute
,I/NetworkMonitor( 4595): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4595/10154)
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4595, uid=10154, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ACRA    ( 4615): ACRA is enabled for com.facebook.katana, intializing...
D/Process (  910): killProcessQuiet, pid=4329
D/PMS     (  910): acquireWL(4468d510): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,I/ActivityManager(  910): Killing 4329:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4615): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4615): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/PMS     (  910): releaseWL(4468d510): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Recipient 4329
,W/SystemClassLoaderAdder( 4615): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4615): Preparing secondary program dexes.
V/DexLibLoader( 4615): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4615): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4615): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4615): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4615): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4615): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4615): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4615): Dex already copied
D/OdexVerifier( 4615): Odex verification is skipped.
,V/DexLibLoader( 4615): Creating class loader
,V/DexLibLoader( 4615): Finished creating class loader
V/DexLibLoader( 4615): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4615): Dex already copied
D/OdexVerifier( 4615): Odex verification is skipped.
,V/DexLibLoader( 4615): Creating class loader,
V/DexLibLoader( 4615): Finished creating class loader,
V/DexLibLoader( 4615): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4615): Dex already copied
D/OdexVerifier( 4615): Odex verification is skipped.
,V/DexLibLoader( 4615): Creating class loader,
V/DexLibLoader( 4615): Finished creating class loader,
V/DexLibLoader( 4615): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4615): Dex already copied
D/OdexVerifier( 4615): Odex verification is skipped.
,V/DexLibLoader( 4615): Creating class loader
,V/DexLibLoader( 4615): Finished creating class loader
,V/DexLibLoader( 4615): Verifying classes from secondary dexes.
,D/DexLibLoader( 4615): DexLibLoader.ensureDexLoaded took 19 ms,
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4256b788
,W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
,W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4256b788, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42408c40
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@426ef870
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
,W/dalvikvm( 4615): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4615): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4615): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4615): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4615): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4615): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4615): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 317ms
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42fbd590)
,D/NfcService( 1255): ScreenObserver: OFF
D/NfcService( 1255): applyRouting - 0
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
D/PMN     (  910): wakingUp
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1255): applyRouting -2
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
I/InputMethodManagerService(  910): Disable input method client, pid=4544
D/PMS     (  910): acquireWL(431aebc0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  910): releaseWL(431aebc0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  910): No lock screen! windowToken=null
D/PMN     (  910): onScreenOn
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): SET_SCREEN_ON:On
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6,
,I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+,
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910): doBoolean: SET pno 0,
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0",
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='0',
I/wpa_supplicant( 1184): wpa_supplicant_scan enter
,D/WifiNative-wlan0(  910):    returned true,
D/PMS     (  910): acquireWL(4268fe68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(4268fe68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 1886): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 1886): [MTP][onReceive]-
D/NfcService( 1255): applyRouting - 0
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/NfcService( 1255): applyRouting -2
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): acquireWL(434f2ff0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/SRS_Proc(  369): ParamSet string: screen_state=on
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
D/PMS     (  910): releaseWL(434f2ff0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1184): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1184): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1184): nl80211: Survey data missing
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1184): Sorted scan results
I/wpa_supplicant( 1184): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1184): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1184): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1184): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1184): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1184): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1184): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1184): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1184): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1184): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1184): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1184): wpa_supplicant_pick_network+
I/wpa_supplicant( 1184): Selecting BSS from priority group 1
I/wpa_supplicant( 1184): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1184): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1184): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
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
I/wpa_supplicant( 1184): wpa_s->is_screen_on 1
I/wpa_supplicant( 1184): wpa_s->ifname wlan0
D/WifiState,Machine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1184): End print parameters
I/wpa_supplicant( 1184): selected network = 1
D/wpa_supplicant( 1184): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb73c94e8  current_ssid=0x0
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
D/wpa_supplicant( 1184): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1184): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1184): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1184): check if in concurrent case
I/wpa_supplicant( 1184): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1184): RSN: PMKSA cache search - network_ctx=0xb73c94e8 try_opportunistic=0
D/wpa_supplicant( 1184): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1184): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1184): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1184): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1184): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1184): nl80211: Unsubscribe mgmt frames handle 0xb73c8718 (mode change)
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1184): nl80211: Subscribe to mgmt frames with non-AP handle 0xb73c8718
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb73c8718
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
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  910): updateScreenOn: false
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1184): reply (489) for get BSS: id=0
I/wpa_supplicant( 1184): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1184): freq=5220
I/wpa_supplicant( 1184): level=-47
I/wpa_supplicant( 1184): tsf=0000000108911492
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=NG7005g
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=1
I/wpa_supplicant( 1184): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): freq=2412
I/wpa_supplicant( 1184): level=-50
I/wpa_supplicant( 1184): tsf=0000000108911506
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=NG700
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=2
I/wpa_supplicant( 1184): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1184): freq=2427
I/wpa_supplicant( 1184): level=-77
I/wpa_supplicant( 1184): tsf=0000000108911520
I/wpa_supplicant( 1184): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1184): ssid=Gonzos
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=3
I/wpa_supplicant( 1184): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): freq=2412
I/wpa_supplicant( 1184): level=-51
I/wpa_supplicant( 1184): tsf=0000000108911513
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1184): ssid=01ABC
I/wpa_supplicant( 1184): ####
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (4) end of scan result ==
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 108911492, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 108911506, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 108911520, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 108911513, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 4 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,I/ClockThread( 1117): stop update clock
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): acquireWL(429bdc28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(429bdc28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(4469e868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1771): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1771): onScreenOn: 1453125231680
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1771): onScreenOn: 1453125231680
D/PMS     (  910): releaseWL(4469e868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42408c40
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42408c40, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@426ef870
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(436f9d90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20766 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  910): doBoolean: SET pno 1
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1184): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1184): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  910):    returned false
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
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
,D/WifiNative-wlan0(  910):    returned true,
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
,V/SRS_Proc(  369): ParamSet string: screen_state=off
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
D/PMS     (  910): acquireWL(434ff1f0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(434ff1f0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
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
D/wpa_supplicant( 1184): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1184): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): TDLS: Remove peers on association
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1184): EAPOL: enable timer tick
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1184): getPrivFuncNum +	
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:,d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1184): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1184): Get randomness: len=32 entropy=5
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/NetworkPolicy(  910): updateScreenOn: false
D/ContactMessageStore( 1239): start background delete task...
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/ContactMessageStore( 1239): size: 0 , 0
D/ContactMessageStore( 1239): Background delete complete
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1184): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb73c89f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1184):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  910): updateConnectedAP...
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1184): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f58b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1184):    broadcast key
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1184): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1184): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1184): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1184): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1184): set send_ind_to_ndc = 0
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1184): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1184): EAPOL authentication completed successfully
I/wpa_supplicant( 1184): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 S,SID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WISPrService( 3850): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3850): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 1
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1184): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(43b49c10): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] getTotalRam: 1873 Mb
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427845b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427845b8 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  910): acquireWL(429a9248): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(429a9248): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4615): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/PMS     (  910): acquireWL(428d5e50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(428d5e50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1771): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1771): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1771): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1771): disableBatteryAlarm: null
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1771): onScreenOff
,W/dalvikvm( 4615): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4615): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4615): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{424619b0 u0 com.test.thalitest/.MainActivity t2}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4615): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4615): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4615): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,I/ActivityManager(  910): Killing 3886:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=3886
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  910): Recipient 3886
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1324): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4653 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
,D/AutoSetting( 1324): Util - no network available!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
,D/AutoSetting( 1324): service - onCreate()
,D/AutoSetting( 1324): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  910): request 41efd1b8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1324): service - mHandler: cancel location update
,D/AutoSetting( 1324): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4615): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4615): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4615): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4653): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4653): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4653): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4653): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4669 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4653/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4653/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4653/10079)
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4683 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  910): Killing 4198:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4198
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/dalvikvm-heap( 4615): Grow heap (frag case) to 9.962MB for 84664-byte allocation
E/dalvikvm( 4615): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4615): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4683): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4615): Grow heap (frag case) to 9.978MB for 28144-byte allocation
,W/ContextImpl( 4683): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4615): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4615): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4615): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4615): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4615): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4615): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;,
W/dalvikvm( 4615): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4615): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4615): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/GAV2    ( 4683): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/dalvikvm( 4615): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4615): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4615): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4615): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4615): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4615): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4615): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4683): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4683): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  910): Recipient 4198
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4615): Grow heap (frag case) to 10.044MB for 39954-byte allocation
,I/dalvikvm-heap( 4615): Grow heap (frag case) to 10.121MB for 79892-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4683/10151)
V/WebViewChromiumFactoryProvider( 4683): Binding Chromium to main looper Looper (main, tid 1) {41e15208}
I/LibraryLoader( 4683): Expected native library version number "",actual native library version number ""
I/chromium( 4683): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4683): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(438db218): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,E/AudioManagerAndroid( 4683): BLUETOOTH permission is missing!
D/PMS     (  910): acquireWL(439cc998): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  910): releaseWL(438db218): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4683): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4683): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4683): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4683): Local Branch: 
I/Adreno-EGL( 4683): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4683): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4683):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4544): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4544): 
,I/NSApplication( 4683): Starting up...
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4683/10151)
D/wpa_supplicant( 1184): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1184): EAPOL: disable timer tick
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4683/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4127/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4127/10160)
,I/dalvikvm-heap( 4615): Grow heap (frag case) to 10.284MB for 75760-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{428509e0 u0 ReceiverList{43615d88 4615 com.facebook.katana/10027/u0 remote:439a6630}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{428509e0 u0 ReceiverList{43615d88 4615 com.facebook.katana/10027/u0 remote:439a6630}}
,D/Process (  910): killProcessQuiet, pid=4363
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4363:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42692eb0 u0 ReceiverList{427a8cf8 4615 com.facebook.katana/10027/u0 remote:4280d680}}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
,I/ActivityManager(  910): Recipient 4363
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/iu.Environment( 2213): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
I/iu.UploadsManager( 2213): num queued entries: 0
I/iu.UploadsManager( 2213): num updated entries: 0
,I/iu.SyncManager( 2213): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4722 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 4722): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4722): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(41fa7418): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4722 1000 null
,D/PMS     (  910): acquireWL(41f5fc88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(41f5fc88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(41fa7418): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4722): getMobilePolicyEnabled, result = true
,I/ActivityManager(  910): Killing 4394:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/Process (  910): killProcessQuiet, pid=4394
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1324): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/TetherSettings( 3850): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3850): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3850): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3850): Cust_ConnectToPC   : spcsc>false
D/        ( 3850): Cust_ConnectToPC   : IPT>true
,D/        ( 3850): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3850): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3850): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3850): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3850): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3850): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3850): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3850): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3850):  defaultType:0
I/ActivityManager(  910): Recipient 4394
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 3850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4544): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4544): 
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/jxcore-log( 4544): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4544): 
,W/ContextImpl( 4615): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4615): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4615): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4722): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4722): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4722): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4722): isEpsOn(), nState = 0
D/WifiService(  910): New client listening to asynchronous messages
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426ef870
,W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
I/jxcore-log( 4544): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4544): 
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426ef870, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426ef870, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426ef870
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4275cec0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4275cec0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/jxcore-log( 4544): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4544): 
,I/jxcore-log( 4544): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4544): 
,I/jxcore-log( 4544): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4544): 
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61,
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  910): releaseWL(43b49c10): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=33 [3][1][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1184): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true,
D/WifiWatchdogStateMachine(  910): WAN detection
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
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
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3850): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42798658
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(42511c50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4653/10079)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(431ea8e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
,I/logwrapper(  362): /system/bin/ip terminated by exit(254)
D/PMS     (  910): releaseWL(42511c50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  910): acquireWL(44663e48): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(431ea8e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2213): Checkin interval check for package: unspecified last checkin: 1453125181844 min interval config: 0 actual interval: 51691
,I/CheckinService( 2213): Checking schedule, now: 1453125233545 next: 1453125211818
,I/CheckinService( 2213): active receiver: enabled
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2213, uid=10029, userID:0
I/CheckinService( 2213): Preparing to send checkin request
,I/EventLogService( 2213): Accumulating logs since 1453125177926
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,I/CheckinRequestBuilder( 2213): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2213): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2213/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4776 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4776): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4776): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4776): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4776): install
,I/MultiDex( 4776): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4776): loading existing secondary dex files
,I/MultiDex( 4776): load found 3 secondary dex files
,I/MultiDex( 4776): install done
,W/dalvikvm( 4776): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4776): VFY: unable to resolve instance field 36
,W/dalvikvm( 4776): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4776): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/jxcore-log( 4544): Test app app.js loaded
I/jxcore-log( 4544): 
,I/Choreographer( 4544): Skipped 272 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4544): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4544): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41e1d190 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  910): releaseWL(436f9d90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/ProviderInstaller( 4776): Installed default security provider GmsCore_OpenSSL
,I/chromium( 4544): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/dalvikvm( 4776): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4776): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4776): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4776): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4776): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4776): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4776): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,D/LocationInitializer( 2213): Restart initialization of location
,E/MDM     ( 1222): [112] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,D/PMS     (  910): acquireWL(43393db8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  910): releaseWL(43393db8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/AuthorizationBluetoothService( 1359): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1359): Proximity feature is not enabled.
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4776): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  369): PrepareKeyRequest: nonce=3129918506
,I/WVCdm   (  369): CdmEngine::CloseSession
,W/Settings( 4776): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4776/10029)
,I/Adreno-EGL( 4776): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4776): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4776): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4776): Local Branch: 
I/Adreno-EGL( 4776): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4776): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4776):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4544): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4544): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4544): BLE advertisement is supported
I/jxcore-log( 4544): 
,D/PMS     (  910): releaseWL(429d2520): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(429f5cd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(429f5cd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=33 [3][1][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,V/Tethering(  910): bSetPropertyMultiRAB:false
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/CaptivePortalTracker(  910): NoActiveNetworkState
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4653/10079)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3929/10053)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(432268c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,I/NetworkMonitor( 4595): type=WIFI subType= reason=null isConnected=true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4595/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/PMS     (  910): releaseWL(432268c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(428426c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
D/PMS     (  910): releaseWL(428426c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1886/10021)
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
,D/AutoSetting( 1324): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4653): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4653): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
,D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1324): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1324): Util - check NLP state, Allowned:false, Enabled:false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4683/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
D/AutoSetting( 1324): service - onStartCommand() check timezone in 30000
D/WVCdm   (  369): PrepareKeyRequest: nonce=1283739959
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4127/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4127/10160)
D/PMS     (  910): acquireWL(440d2520): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(440d2520): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2213): Checkin interval check for package: unspecified last checkin: 1453125181844 min interval config: 0 actual interval: 52810
,I/dalvikvm-heap( 4127): Grow heap (frag case) to 13.529MB for 1821008-byte allocation
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2213, uid=10029, userID:0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/iu.Environment( 2213): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2213): num queued entries: 0
I/iu.UploadsManager( 2213): num updated entries: 0
,I/iu.SyncManager( 2213): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): acquireWL(429bd950): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,I/WVCdm   (  369): CdmEngine::CloseSession
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
,D/libc    ( 1359): [NET] getaddrinfo_proxy+
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =95ef +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] NOT IN CACHE
,I/Adreno-EGL( 4776): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4776): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4776): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4776): Local Branch: 
I/Adreno-EGL( 4776): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4776): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4776):                  aa63bbd948f41d15fc72f585e
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 212
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4776): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4776): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4776): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4776): Local Branch: 
I/Adreno-EGL( 4776): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4776): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4776):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): acquireWL(4413bdf0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): releaseWL(429bd950): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(4413bdf0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4327cad8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(4327cad8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2213): Classify the device as Phone.
,D/libc    ( 2213): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2213): [NET] getaddrinfo-,err=8
D/libc    ( 2213): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2213): [NET] getaddrinfo-, 1
,D/libc    ( 2213): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =e7d0 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 94
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2213): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2213): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2213): [NET] getaddrinfo-,err=8
,D/libc    ( 2213): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2213): [NET] getaddrinfo-,err=8
,D/libc    ( 2213): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2213): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2213): Sending checkin request (12200 bytes)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,W/fb4a(:<default>):UserScope( 4615): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4615): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=20 [24][5][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4615): Called registerBroadcastReceiver twice.
,D/PMS     (  910): releaseWL(439cc998): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  910): acquireWL(431e4a60): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4595 10154 null
,W/ContextImpl( 4595): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4595): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4595, uid=10154, userID:0
,I/MusicLeanback( 4595): Conditions not met for autocaching.
,I/MusicLeanback( 4595): Stop autocaching.
D/PMS     (  910): releaseWL(431e4a60): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,I/CheckinRequestBuilder( 2213): Checkin reason type: 8 attempt count: 1
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2213): Failed to find provider info for com.google.android.wearable.settings
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4615/10027)
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2213/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
,I/CheckinRequestBuilder( 2213): Classify the device as Phone.
,I/CheckinTask( 2213): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2213): Checking schedule, now: 1453125235943 next: 1453648172938
,I/CheckinService( 2213): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2213, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,I/CheckinService( 2213): Checking schedule, now: 1453125235966 next: 1453648172938
,I/CheckinService( 2213): active receiver: disabled
,D/CheckinService( 2213): Recording last checkin time for package unspecified as 1453125235972
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2213, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(44663e48): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2213/10029)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
D/libc    (  910): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =a0fa +++++
,D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE,
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4683): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1495): service - handleMessage() stop self
,D/AutoSetting( 1495): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=4417
,I/ActivityManager(  910): Killing 4417:com.htc.backup/1000 (adj 15): empty #17
D/AutoSetting( 1495): service - handleMessage() quit looper
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4417
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  910): acquireWL(4362ada8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4234f1f8: PendingIntentRecord{4234f170 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=117295, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4362ada8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  910): killProcessQuiet, pid=4380
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4380:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4380
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1324): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1324): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1324): service - requestNLP() NetworkLocationProvider not enabled
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4833 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsUpdated
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4833): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4833): MmsConfig.loadMmsSettings
,W/dalvikvm( 4833): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4833): VFY: unable to resolve instance field 36
,W/dalvikvm( 4833): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4833): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4857 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4833, uid=10111, userID:0
,W/Settings( 4833): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4857): onCreate
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4833, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4833, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4833, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4833, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4833, uid=10111, userID:0
,W/PackageManager(  910): Unable to load service info ResolveInfo{441f2c48 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/ProviderInstaller( 4833): Installed default security provider GmsCore_OpenSSL
,V/GetPrviateResource( 4857): GetPrviateResource
,V/GetPrviateResource( 4857): GetPrviateResource
,D/MmsCustomizationProvider( 4857): query uri: content://htc-mms-customization/mms-ua/ua_string
D/PMS     (  910): acquireWL(446f0598): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4833 10111 null
,D/MmsCustomizationProvider( 4857): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/Babel   ( 4833): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4833): MmsConfig.loadFromDatabase
I/[PluginManager]RegisterService( 1324): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1324): handle notify Blinkfeed plugin client changed
,D/Process (  910): killProcessQuiet, pid=3929
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  910): Killing 3929:com.htc.musicenhancer/u0a53 (adj 15): empty #17
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Recipient 3929
,I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2874): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
E/Babel   ( 4833): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4833): MmsConfig.loadFromResources
,E/Babel   ( 4833): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4833): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4857): sense_version=6.0
,D/BTAccessoryUtil( 4857): createReceiver
D/PMS     (  910): releaseWL(446f0598): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  910): killProcessQuiet, pid=4438
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/BTAccessoryUtil( 4857): registerReceiver return intent = null
D/MessageCustFlag( 4857): sku_id=99
,W/SystemReader( 4857): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  910): Killing 4438:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/PMS     (  910): acquireWL(44626290): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Recipient 4438
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Messaging( 4857): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4857): networkCode: 
D/MessageCustFlag( 4857): sku_id=99
D/MmsConfig( 4857): SIE smsPri: null
D/MmsConfig( 4857): networkCode: 
D/HtcTelephonyCapability( 4857): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4857): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4857): getRATByHtcTelephonyCapability:1
W/SystemReader( 4857): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  910): releaseWL(44626290): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(44198558): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4127): Grow heap (frag case) to 15.227MB for 1821008-byte allocation
,D/PMS     (  910): releaseWL(44198558): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4127): Grow heap (frag case) to 16.957MB for 1821008-byte allocation
D/PMS     (  910): acquireWL(44160460): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(44160060): PARTIAL_WAKE_LOCK  AsyncService 0x1 4127 10160 null
D/PMS     (  910): releaseWL(44160060): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): releaseWL(44160460): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(44140ab0): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10029 WorkSource{10029 com.google.android.gms},
,I/ActivityManager(  910): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,D/PMS     (  910): releaseWL(44140ab0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  910): acquireWL(429a1958): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  910): releaseWL(429a1958): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  910): acquireWL(427ef3b0): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(426498b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(426498b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(427ef3b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
I/ActivityManager(  910): Resuming delayed broadcast
D/PMS     (  910): acquireWL(429a0cd0): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42897a28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42897a28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42623450): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(429a0cd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42623450): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2213): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2213): Null package name or gms related package.  Ignoreing.
D/PMS     (  910): acquireWL(427ace00): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2213): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2874): UpdateCorporaTask done [took 387 ms] updated apps [took 387 ms] 
I/ActivityManager(  910): Resuming delayed broadcast
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41ea3c38 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41ea3c38 -
,I/Icing   ( 2213): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,I/Icing   ( 2213): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(427ace00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4857): mNeedToUpdateDate2 start
,D/MmsConfig( 4857): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4857): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4857): 
D/MmsAsyncWorkHandler( 4857): HM tk = 20001
,D/ReportIndicatorCache( 4857): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4857): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41e17490
,I/Messaging( 4857): mccmnc> 
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4857): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4857): [DraftCache/1] refresh
,D/MmsConfig( 4857): networkCode: 
,D/Messaging( 4857): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4857): sense_version=6.0
D/Jerry   ( 4857): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4857): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4857): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4857): createReceiver
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1239): sku_id=99
D/TelephUtils( 1239): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1239): Update uri=content://mms, match=0
,V/MmsProvider( 1239): selection=st=129 AND m_type!=134
D/Messaging( 4857): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4857): TransactionService is going to be woken up.
,D/DraftCache( 4857): [DraftCache/478] rebuildCache
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1239):  phoneType = -1
,V/TransactionService( 4857): 1-Creating TransactionService
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
V/TransactionService( 4857): onStartCommand: 1
,D/MmsSystemEventReceiver( 4857): unRegisterForConnectionStateChanges
V/TransactionService( 4857): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4857): Loading previous transactions.
,D/Messaging( 4857): mNeedToUpdateDate2: false
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1239): device_type: 1
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/Messaging( 4857): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MmsSmsV2Provider( 1239):  phoneType = -1
D/TransactionService( 4857): Force set service start id to 1
V/TransactionService( 4857): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4857): unRegisterForConnectionStateChanges
,D/TransactionService( 4857): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4857): Destroying TransactionService
,V/TransactionService( 4857): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/Jerry   ( 1239): URI_DRAFT
,D/Messaging( 4857): ViewCache CreatePreload
,D/Messaging( 4857): ViewCache CreatePreloadOnlyMultipleOpsList
D/DraftCache( 4857): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4857): [DraftCache/478] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4857): 
D/MmsAsyncWorkHandler( 4857): HM tk = 20002
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1239): sku_id=99
,D/Cust_MMSMS( 4857): _has_set_default_values_2=true
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1239): sku_id=99
,D/MsgPreferenceUtils( 4857): def_index: 0
,D/MsgPreferenceUtils( 4857): globalIndex = 1
D/MsgPreferenceUtils( 4857): phone state: true
D/MsgPreferenceUtils( 4857): sd state: false
,D/MsgPreferenceUtils( 4857): vIndex = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{435ca3c0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4833): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(42716050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(42716050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42631970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{429bf808: PendingIntentRecord{42931ea8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=128439, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{4294b3f0: PendingIntentRecord{4293cc88 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=139126, Int=0
,D/PMS     (  910): acquireWL(43b39ac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=23 [17][4][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(4315f218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4315f218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43b39ac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42631970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(428a3fc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(428a3fc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43c20610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): acquireWL(435017b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43bf6ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1453125262165 tag=VacuumService
,D/PMS     (  910): releaseWL(43c20610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(435017b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43bf6ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43b4a7e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(43b4a7e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43b46098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(43b46098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(441c98f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(441c98f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(446c6f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(446c6f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4325e3a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): acquireWL(43dc9990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43dc9990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(434fe378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4325e3a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4410df18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(4410df18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 9276 seconds from now (1453125262824)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =dd9c +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 211
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4,
D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(434fe378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(428c5100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(428c5100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44572628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025089
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025220
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025276
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025280
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025288
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025296
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028314
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028339
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360031423
,D/PMS     (  910): releaseWL(44572628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1324): service - has update message, not stop
,D/AutoSetting( 1324): service - mHandler: update timezone
,D/AutoSetting( 1495): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1495): service - onCreate(),
,D/AutoSetting( 1495): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1495): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1572): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1495): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1495): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1495): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1495): service - mHandler: update timezone
,D/AutoSetting( 1495): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1495): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1495): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1495): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42230dc0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 8 3 11
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  910): acquireWL(44131908): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): acquireWL(43111648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{426c3540: PendingIntentRecord{426cc578 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142269, Int=0
D/PMS     (  910): releaseWL(43111648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =f705 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE,
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=238
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(44131908): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44242d20 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(43497dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(43497dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1324): service - handleMessage() stop self
,D/AutoSetting( 1324): service - handleMessage() quit looper
,D/AutoSetting( 1324): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=4471
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4471:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4471
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1495): service - handleMessage() stop self
,D/AutoSetting( 1495): service - onDestroy() END
,D/AutoSetting( 1495): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4485
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Killing 4485:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4485
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(42910fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{43224bb0: PendingIntentRecord{43e52e30 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175434, Int=0
,D/PMS     (  910): releaseWL(42910fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  910): acquireWL(441265c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4234f1f8: PendingIntentRecord{4234f170 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=177295, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(441265c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(429e3ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(429e3ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(438e00c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-,
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(438e00c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(436168f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4234f1f8: PendingIntentRecord{4234f170 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=237296, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(436168f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(438df950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(438df950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(42924978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42924978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
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
,D/PMS     (  910): acquireWL(43126248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4234f1f8: PendingIntentRecord{4234f170 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=297295, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43126248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4465ac68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4465ac68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4544): --= Surplus to requirements =--
I/jxcore-log( 4544): 
I/jxcore-log( 4544): ****TEST TOOK:  ms ****
I/jxcore-log( 4544): 
,I/jxcore-log( 4544): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4544): 
,E/cutils-trace( 4952): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4952): ====startRecUseTime====
D/htc.customization.log.level( 4952):  is 
,W/CustomizationLogLevel( 4952): Level value is invalid, use default level 2
,D/CustomizationManager( 4952):  Read ACC file spent 0.098 (s)
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4952): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4952): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4952): Parsing tag category name = system
I/CustomizationCIDLoader( 4952): Parsing tag category name = application
I/CustomizationCIDLoader( 4952): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4952): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4952): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4952): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4952): Parsing tag category name = Settings
,D/CustomizationManager( 4952):  Read CID file spent 0.152 (s)
,D/CustomizationManager( 4952):  All configurations done spent 0.153 (s)
,W/HtcNativeFlag( 4952): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4952): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4952): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4952): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4952, uid=2000 user=0
,I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  910): killProcessQuiet, pid=4544
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  910): Killing 4544:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  910):   Force finishing activity ActivityRecord{424619b0 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  910): Copying FileAsset 0x69d3ec18 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  910): channel '42693740 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  910): channel '42693740 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  910): Attempted to unregister already unregistered input channel '42693740 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowManager(  910): WINDOW DIED Window{42693740 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  910): Client connection lost with reason: 4
,W/WindowManager(  910): Failed looking up window
W/WindowManager(  910): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@431521d0 does not exist
W/WindowManager(  910): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  910): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  910): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  910): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  910): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  910): WIN DEATH: null
,W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4544 uid 10389
W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
,W/PackageSettings(  910): Skipping PackageSetting{4251af38 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): acquireWL(44209ea8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(44209ea8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.,
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/[PluginManager]RegisterService( 1324): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/[PluginManager]RegisterService( 1324): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
,I/IcingCorporaProvider( 2874): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4967 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  910): acquireWL(44622048): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2874): UpdateCorporaTask done [took 353 ms] updated apps [took 352 ms] 
,E/SQLiteDatabase( 4967): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4967): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4967): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4967): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4967): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4967): 	at aJm.a(Scopes.java:65)
,E/SQLiteDatabase( 4967): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4967): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4967): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4967): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4967): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4967): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4967): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4967): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4967): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4967): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4967): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4967): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4967): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4967): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4967): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4967): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4967): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4967): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4967): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4967): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4967): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4967): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4967): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4967): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4967): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4967): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4967): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4967): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4967): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4967): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4967): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4967): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4967): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4967): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4967): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4967): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4967): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4967): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4967): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4967): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4967): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4967): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4967): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4967): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4967): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4967): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4967): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4967): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4967): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4967): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4967): threadid=11: thread exiting with uncaught exception (group=0x419dee30)
,E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4967): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4967): Process: com.google.android.apps.docs, PID: 4967
E/AndroidRuntime( 4967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4967): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4967): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4967): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4967): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4967): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4967): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 4967): killProcess, pid=4967
,D/Process ( 4967): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4985 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  910): Recipient 4967
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4967) has died.
,W/ContextImpl( 4985): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4985): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4985): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4985): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4985): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4985): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4985): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4985): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4985): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4985): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4985): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4985): threadid=10: thread exiting with uncaught exception (group=0x419dee30)
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4998 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/AndroidRuntime( 4985): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4985): Process: com.android.keychain, PID: 4985
E/AndroidRuntime( 4985): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4985): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4985): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4985): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4985): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4985): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4985): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4985): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4985): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  910): App crashed! Process: com.android.keychain
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4985): killProcess, pid=4985
,D/Process ( 4985): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453125438380.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4985
I/ActivityManager(  910): Process com.android.keychain (pid 4985) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/AppTag  ( 4998): getInstance(Context context)
,W/PackageManager(  910): Unable to load service info ResolveInfo{427af968 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/AppTag  ( 4998): getInstance(Context context)
,D/AppTag  ( 4998): onCreate()
,D/PMS     (  910): acquireWL(42a29b50): PARTIAL_WAKE_LOCK  AsyncService 0x1 4127 10160 null
,D/PMS     (  910): releaseWL(42a29b50): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4153): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,I/ActivityManager(  910): Killing 4089:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4089
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PackageBroadcastService( 2213): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2213): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2213): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2213): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2213): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2213): Module APK com.google.android.play.games already loaded
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2213): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2213): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e5f7498
,W/dalvikvm( 2213): threadid=45: thread exiting with uncaught exception (group=0x419dee30)
E/SQLiteLog( 2213): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2213): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65358bf8
,E/ActivityManager(  910): App crashed! Process: com.google.android.gms
,I/LocationSettingsChecker( 2213): Removing dialog suppression flag for package com.test.thalitest
,E/DriveAsyncService( 2213): disk I/O error (code 3850)
E/DriveAsyncService( 2213): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2213): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2213): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2213): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2213): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2213): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2213): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2213): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2213): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2213): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2213): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2213): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2213): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2213): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2213): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2213): 	at java.lang.Thread.run(Thread.java:864)
,D/Process ( 2213): killProcess, pid=2213
,D/Process ( 2213): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 2213): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2213): Process: com.google.android.gms, PID: 2213
E/AndroidRuntime( 2213): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2213): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2213): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2213): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2213): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2213): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2213): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2213): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2213): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2213): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2213): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2213): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
,E/AndroidRuntime( 2213): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2213): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2213): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2213): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2213): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2213): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2213): 	at java.lang.Thread.run(Thread.java:864)
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  910): Recipient 4089
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 2213
D/WifiService(  910): Client connection lost with reason: 4
,D/PMS     (  910): handleWLDeath(44622048): PARTIAL_WAKE_LOCK  Icing 0x1
,I/ActivityManager(  910): Process com.google.android.gms (pid 2213) has died.
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10998ms
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20997ms
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20996ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30996ms
,I/ActivityManager(  910): Resuming delayed broadcast
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30993ms
,E/SQLiteLog( 1359): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1359): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5c93ca18
,W/dalvikvm( 1359): threadid=1: thread exiting with uncaught exception (group=0x419dee30)
,E/AndroidRuntime( 1359): FATAL EXCEPTION: main
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
,E/ActivityManager(  910): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 1359): killProcess, pid=1359
,D/Process ( 1359): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5028 uid=10098 gids={50098, 3003, 5012}
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,I/DeviceManagement( 5028): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5028 dbg=false s=true
,I/DeviceManagement( 5028): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 5028): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 5028): WorkflowService: Starting workflow service
,W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/DeviceManagement( 5028): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41e40e58] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5028): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5028): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5028): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 5028): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5042 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 5028): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 5028): SessionStateController: Checking invariants...
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41ea3c38 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,D/Documents( 5042): Loading roots for com.android.providers.downloads.documents
,D/Documents( 5042): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 5042): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5042): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5042): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5042): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5042): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5042): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5042): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5042): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5042): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5042): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5042): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5042): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5042): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5042): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5042): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5042): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5042): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5042): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 5042): threadid=1: thread exiting with uncaught exception (group=0x419dee30)
E/AndroidRuntime( 5042): FATAL EXCEPTION: main
E/AndroidRuntime( 5042): Process: com.android.documentsui, PID: 5042
E/AndroidRuntime( 5042): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5042): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5042): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5042): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5042): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5042): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5042): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5042): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5042): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5042): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5042): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5042): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5042): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5042): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5042): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5042): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5042): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5042): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5042): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5042): 	... 10 more
I/ActivityManager(  910): Recipient 1359
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
,I/ActivityManager(  910): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5057 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/Process (  910): killProcessQuiet, pid=4515
,I/ActivityManager(  910): Killing 4515:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/ActivityManager(  910): App crashed! Process: com.android.documentsui
I/ActivityManager(  910): Process com.google.process.gapps (pid 1359) has died.
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30757ms
,E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453125438844.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  910): Recipient 4515
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5070 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  910): killProcessQuiet, pid=4722
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
,I/ActivityManager(  910): Killing 4722:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process ( 5042): killProcess, pid=5042
D/Process ( 5042): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4722
,D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Recipient 5042
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Process com.android.documentsui (pid 5042) has died.
,E/SQLiteDatabase( 5028): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5028): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5028): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5028): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5028): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5028): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5028): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5028): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5028): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 5028): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5028): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5028): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5028): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5028): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5028): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 5057): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
I/DeviceManagement( 5028): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5028): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 5028): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,W/dalvikvm( 5057): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/ExternalStorage( 5070): After updating volumes, found 1 active roots
I/MultiDex( 5057): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5057): install
,E/SQLiteDatabase( 5028): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5028): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5028): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5028): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5028): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5028): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5028): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5028): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5028): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 5057): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,W/DeviceManagement( 5028): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41e40e58]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 5028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 5028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 5028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5028): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5028): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5028): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5028): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5028): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5028): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5028): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5028): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 5028): WorkflowService: Stopping workflow service
,I/MultiDex( 5057): loading existing secondary dex files
,I/MultiDex( 5057): load found 3 secondary dex files
,I/MultiDex( 5057): install done

```
