#### Test 549702617cfd775_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1119): WifiActivity: 1
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/ActivityManager(  910): Waited long enough for: ServiceRecord{4468bbc0 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4443): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4443): ====startRecUseTime====
D/htc.customization.log.level( 4443):  is 
W/CustomizationLogLevel( 4443): Level value is invalid, use default level 2
D/CustomizationManager( 4443):  Read ACC file spent 0.050 (s)
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
D/CustomizationManager( 4443):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4443):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4443): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4443): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4443): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4443): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4443
D/PMS     (  910): acquireHCC(4243ba08): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(423c9048): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x637b9f78 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1112016280
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b70750
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  910): acquireWL(422c23a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4454 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4454): Copying FileAsset 0x5c700428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4454): Binding Chromium to main looper Looper (main, tid 1) {41a82618}
I/LibraryLoader( 4454): Expected native library version number "",actual native library version number ""
I/chromium( 4454): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4454): Initializing chromium process, renderers=0
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41d3bf90:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4454): 1101627472: getState(). Returning 12
D/PMS     (  910): acquireWL(41fd8020): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  910): acquireWL(41e57e70): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  910): releaseWL(41e57e70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4454): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4454): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4454): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4454): Local Branch: 
I/Adreno-EGL( 4454): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4454): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4454):                  aa63bbd948f41d15fc72f585e
W/chromium( 4454): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4454): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4454): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4454): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4454): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4454): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4454): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4454): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4454): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4454): CordovaWebView is running on device made by: HTC
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
W/AwContents( 4454): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  910): Disable input method client, pid=1273
,W/ResourceType( 4454): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4454): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ac9700, mServedView=org.apache.cordova.engine.SystemWebView{41a8f368 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  910): Enable input method client, pid=4454
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4454): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +254ms
,D/PMS     (  910): releaseWL(422c23a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4454): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4454): JniHelper::setJavaVM(0x41557048), pthread_self() = 1662112664
,D/JX-Cordova( 4454): jxcore cordova android initializing
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.557MB for 63974-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.588MB for 95956-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.661MB for 143930-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.776MB for 215890-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.951MB for 323830-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 12.626MB for 728606-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 13.223MB for 1092904-byte allocation
,D/PMS     (  910): acquireWL(42347500): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 14.087MB for 1639352-byte allocation
D/PMS     (  910): releaseWL(42347500): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(41d6d7c8): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(41d6d7c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(4257b148): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(4257b148): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 15.450MB for 2459024-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 17.430MB for 3688532-byte allocation
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 4454): Initializing JXcore engine
,W/jxcore-log( 4454): JXcore engine is ready
,W/jxcore-log( 4454): Starting JXcore engine
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
D/PMS     (  910): releaseHCC(4243ba08): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(423c9048): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4454): Platform android
W/jxcore-log( 4454): 
,W/jxcore-log( 4454): Process ARCH arm
W/jxcore-log( 4454): 
,I/jxcore-log( 4454): JXcore Cordova bridge is ready!
I/jxcore-log( 4454): 
,W/jxcore-log( 4454): JXcore engine is started
,I/chromium( 4454): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4454): Toggling radios to true
I/jxcore-log( 4454): 
,D/BluetoothAdapter( 4454): enable(): BT is already enabled..!
,D/WifiManager( 4454): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1103
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump,
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
D/WifiService(  910): New client listening to asynchronous messages
D/WifiService(  910): setWifiEnabled: true pid=4454, uid=10348
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
W/Settings:Agent(  910): << traceCallingStack(): 2(ms)
D/WifiManager( 4454): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
D/WifiManager( 4454): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): TDLS: Tear down peers
I/wpa_supplicant( 1179): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4454): Radios toggled
I/jxcore-log( 4454): 
I/jxcore-log( 4454): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4454): 
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1179): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1179): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb72eabc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1179): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1179): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1179): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: Extern,al notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  910):    returned true
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  910): acquireWL(43fb7438): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): Fast associate: Old scan results
I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  910):    returned true
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19606 mDataStallAlarmIntent=PendingIntent{421b9af8: PendingIntentRecord{424ac0b0 android broadcastIntent}}
,D/WifiStateMachine(  910): Enter handleNetworkDisconnect
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1833/10178)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/UsbnetStateTracker(  910): isAvailable+-
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4229): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4229): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiService(  910): New client listening to asynchronous messages
D/WISPrService( 4229): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4229): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/libc    (  365): [NET] entry_id:5   entry:0xb86108e0  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb86157c8  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8615718  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8615548  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8615890  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb8615610  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb86154b0  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb8615180  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/PMS     (  910): acquireWL(423cc5d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1409 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1833/10178)
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  910): acquireWL(424fbeb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SCAN
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1409/10028)
D/PMS     (  910): acquireWL(43fdcd88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1409 10028 null
D/PMS     (  910): releaseWL(423cc5d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
,D/BatSI   (  910): WIFI scan started for: 650a0300 uid:1000
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  910):    returned false
D/PMS     (  910): releaseWL(43fdcd88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/PMS     (  910): releaseWL(424fbeb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ActivityManager(  910): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4511 uid=10077 gids={50077}
,D/PMS     (  910): acquireWL(424bbeb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10077}
,V/AlarmManager(  910): sending alarm PendingIntent{42262120: PendingIntentRecord{41b00e90 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452520906669, Int=60000
,D/PMS     (  910): releaseWL(424bbeb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4511): SMSBackupAgentService started
,D/SMSBackup( 4511): Checking restore status
D/SMSBackup( 4511): Restore complete
,D/SMSBackup( 4511): cancelCheckAlarm
,D/SMSBackup( 4511): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  910): killProcessQuiet, pid=3170
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3170:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  910): releaseWL(41fd8020): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3170
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  910): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4345/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1833/10178)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (3950/10154)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1877/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/PMS     (  910): acquireWL(42288350): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/CaptivePortalTracker(  910): NoActiveNetworkState
I/NetworkMonitor( 3950): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1505/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4345/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2382/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4525 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4525): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4525): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4525): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4525): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4525): Preparing secondary program dexes.
V/DexLibLoader( 4525): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4525): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4525): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4525): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4525): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4525): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4525): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4525): Dex already copied
D/OdexVerifier( 4525): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4525): Creating class loader
,V/DexLibLoader( 4525): Finished creating class loader
V/DexLibLoader( 4525): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4525): Dex already copied
D/OdexVerifier( 4525): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4525): Creating class loader
,V/DexLibLoader( 4525): Finished creating class loader
V/DexLibLoader( 4525): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4525): Dex already copied
D/OdexVerifier( 4525): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4525): Creating class loader
V/DexLibLoader( 4525): Finished creating class loader
V/DexLibLoader( 4525): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4525): Dex already copied
D/OdexVerifier( 4525): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4525): Creating class loader
,V/DexLibLoader( 4525): Finished creating class loader
,V/DexLibLoader( 4525): Verifying classes from secondary dexes.
,D/DexLibLoader( 4525): DexLibLoader.ensureDexLoaded took 17 ms
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  910): releaseWL(42288350): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/SensorManager(  910): mEventCount = 1350
,W/dalvikvm( 4525): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4525): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4525): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4525): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4525): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4525): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4525): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4525): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1179): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1179): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-82
I/wpa_supplicant( 1179): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1179): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1179): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1179): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1179): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1179): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1179): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 3
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 1
I/wpa_supplicant( 1179): wpa_s->is_screen_on 1
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): selected network = 1
D/wpa_supplicant( 1179): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb72ec4e8  current_ssid=0x0
D/w,pa_supplicant( 1179): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1179): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1179): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1179): check if in concurrent case
I/wpa_supplicant( 1179): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1179): RSN: PMKSA cache search - network_ctx=0xb72ec4e8 try_opportunistic=0
D/wpa_supplicant( 1179): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1179): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1179): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1179): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1179): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1179): nl80211: Unsubscribe mgmt frames handle 0xb72eb718 (mode change)
D/wpa_supplicant( 1179): nl80211: Subscribe to mgmt frames with non-AP handle 0xb72eb718
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb72eb718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1179):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1179):   * freq=2412
D/wpa_supplicant( 1179):   * Auth Type 0
D/wpa_supplicant( 1179):   * WPA Versions 0x2
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1179): nl80211: Connect request send successfully
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1179): reply (779) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-47
I/wpa_supplicant( 1179): tsf=0000000105801216
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-52
I/wpa_supplicant( 1179): tsf=0000000105801234
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=2
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2452
I/wpa_supplicant( 1179): level=-77
I/wpa_supplicant( 1179): tsf=0000000105801246
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=3
I/wpa_supplicant( 1179): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1179): freq=2437
I/wpa_supplicant( 1179): level=-82
I/wpa_supplicant( 1179): tsf=0000000105801253
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=UPC5999698
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1179): freq=2437
I/wpa_supplicant( 1179): level=-84
I/wpa_supplicant( 1179): tsf=0000000105801250
I/wpa_supplicant( 1179): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=UPC Wi-Free
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=5
I/wpa_supplicant( 1179): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-53
I/wpa_supplicant( 1179): tsf=0000000105801228
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1179): ssid=01ABC
I/wpa_supplicant( 1179): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,W/dalvikvm( 4525): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (6) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 105801216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 105801234, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 105801246, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -82, frequency: 2437, timestamp: 105801253, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 105801250, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 105801228, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 6 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,E/FbInjectorInitializer( 4525): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Connect event
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1179): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1179): Add randomness: count=14 entropy=6
I/wpa_supplicant( 1179): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): TDLS: Remove peers on association
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1179): EAPOL: enable timer tick
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1179): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1179): Get randomness: len=32 entropy=7
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb72eb9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f8cb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1179):    broadcast key
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1179): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1179): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1179): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiApDatabaseHandler(  910): updateConnectedAP...
E/wpa_supplicant( 1179): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1179): set send_ind_to_ndc = 0
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1179): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1179): EAPOL authentication completed successfully
I/wpa_supplicant( 1179): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WISPrService( 4229): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4229): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 1
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(4317adb0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424e8540 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424e8540 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4525): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4525): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4525): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=3933
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 3933:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  910): acquireWL(4365b3e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10028 null
,D/PMS     (  910): acquireWL(43bdf780): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(4365b3e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/PMS     (  910): releaseWL(43bdf780): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1409): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/AutoSetting( 1398): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Recipient 3933
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4555 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
,D/AutoSetting( 1398): Util - no network available!
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
D/AutoSetting( 1398): service - onCreate()
D/AutoSetting( 1398): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  910): request 42490bc8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1398): service - mHandler: cancel location update
,D/AutoSetting( 1398): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4525): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4525): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4525): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4555): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4555): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4555): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4555): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4571 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10078)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10078)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10078)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4525): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/dalvikvm( 4525): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4525): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4525): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4525): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4525): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4525): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4525): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4525): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4525): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4525): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4525): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4525): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4525): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4525): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4525): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4525): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4525): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4525): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4588 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=4286
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 4286:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4286
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 9.920MB for 39954-byte allocation
D/WifiService(  910): Client connection lost with reason: 4
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 9.997MB for 79892-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4588): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4588): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4588): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4588): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4588): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 10.067MB for 84664-byte allocation
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 10.093MB for 28144-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4588/10151)
,V/WebViewChromiumFactoryProvider( 4588): Binding Chromium to main looper Looper (main, tid 1) {41a87370}
,I/LibraryLoader( 4588): Expected native library version number "",actual native library version number ""
,I/chromium( 4588): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4588): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(42541970): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,E/AudioManagerAndroid( 4588): BLUETOOTH permission is missing!
D/PMS     (  910): acquireWL(42b70108): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  910): releaseWL(42541970): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4588): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4588): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4588): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4588): Local Branch: 
I/Adreno-EGL( 4588): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4588): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4588):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4588): Starting up...
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4588/10151)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4588/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{435201c0 u0 ReceiverList{43411a38 4525 com.facebook.katana/10026/u0 remote:43371518}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{435201c0 u0 ReceiverList{43411a38 4525 com.facebook.katana/10026/u0 remote:43371518}}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4208/10160)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{440686f8 u0 ReceiverList{44024d48 4525 com.facebook.katana/10026/u0 remote:44021e58}}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4208/10160)
,D/Process (  910): killProcessQuiet, pid=4315
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4315:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1833/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1833/10178)
I/ActivityManager(  910): Recipient 4315
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/GCM     ( 1409): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/PMS     (  910): acquireWL(4252e080): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
,D/PMS     (  910): releaseWL(4252e080): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1505): Unknown pending intent to remove.
D/PMS     (  910): acquireWL(43775178): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
D/PMS     (  910): releaseWL(43775178): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4525): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4525): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1179): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1179): EAPOL: disable timer tick
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  910): releaseWL(4317adb0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1179): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
,D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19608 delay=15s
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  910): WAN detection
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4229): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1833/10178)
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@423afc40
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
,D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(43247a78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10078)
D/PMS     (  910): acquireWL(4352eba0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10028 null
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  910): acquireWL(43554808): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2228 10028 null
D/PMS     (  910): releaseWL(4352eba0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/CheckinService( 2228): Preparing to send checkin request
,I/EventLogService( 2228): Accumulating logs since 1452520857718
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2228): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2228): Using GMS GoogleHttpClient
D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(43247a78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2228/10028)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.gms (2228/10028)
,W/GLSUser ( 1409): GoogleAccountDataService.getToken()
,W/GLSActivity( 1409): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1409): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1409): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2228): awaiting user notification for token
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ac95d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 2 20 3 12
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4664 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4664): install
,I/MultiDex( 4664): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4664): loading existing secondary dex files
,I/MultiDex( 4664): load found 1 secondary dex files
,I/MultiDex( 4664): install done
,I/ProviderInstaller( 4664): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1409): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/Settings( 4664): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WIFI_ICON( 1119): WifiActivity: 3
,D/PMS     (  910): releaseWL(43fb7438): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  910): NoActiveNetworkState
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10078)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (3950/10154)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1505/10028)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/NetworkMonitor( 3950): type=WIFI subType= reason=null isConnected=true
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4353a498): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1833/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1877/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
I/acms    ( 1877): Checking Certificates
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
I/acms    ( 1877): Checking Developer Certificates
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/acms    ( 1877): Checking Application Certificates
I/acms    ( 1877): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1877): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1877): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1877): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1877): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1877): Updating next query delay: 75600000
I/mlserverapp( 1877): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1877): cancelACMSProgrammedChecks
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3972/10051)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4345/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42f49d78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4345/10100)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
D/PMS     (  910): releaseWL(42f49d78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(4353a498): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2382/10021)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/PMS     (  910): acquireWL(423f5c20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(423f5c20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1409): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
D/libc    ( 1409): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1409): [NET] getaddrinfo-,err=8
,D/libc    ( 1409): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1409): [NET] getaddrinfo-, 1
D/libc    ( 1409): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =cba6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/PMS     (  910): acquireWL(440baa10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1409 10028 null
,D/AutoSetting( 1398): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4555): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4555): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1398): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1398): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1398): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1398): service - handleMessage() setting current location null
,D/AutoSetting( 1398): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1398): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4588/10151)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4208/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4208/10160)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 244
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1409): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1833/10178)
,I/dalvikvm-heap( 4208): Grow heap (frag case) to 13.520MB for 1821008-byte allocation
,I/Adreno-EGL( 4664): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4664): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4664): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4664): Local Branch: 
I/Adreno-EGL( 4664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4664): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4664):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1409): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1409): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/PMS     (  910): acquireWL(42485e88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1409 10028 null
D/PMS     (  910): releaseWL(42485e88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4664): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4664): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4664): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4664): Local Branch: 
I/Adreno-EGL( 4664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4664): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4664):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4664): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4664): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4664): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4664): Local Branch: 
I/Adreno-EGL( 4664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4664): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4664):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [6][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  910): BroadcastRSSIForIMS, newrssi =-52 , oldRssi= -200
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/GCM     ( 1409): Connected
D/PMS     (  910): acquireWL(422983c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1409 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/PMS     (  910): releaseWL(440baa10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1409/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/PMS     (  910): releaseWL(422983c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  910): acquireWL(425441a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1409 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4664/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1409/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/GCM     ( 1409): Message class mpf
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1409/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
I/CheckinTask( 2228): Sending checkin request (8880 bytes)
D/libc    ( 2228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2228): [NET] getaddrinfo-,err=8
D/libc    ( 2228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2228): [NET] getaddrinfo-, 1
D/libc    ( 2228): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =79d1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
W/fb4a(:<default>):UserScope( 4525): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  910): acquireWL(42345920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1409 10028 null
D/PMS     (  910): releaseWL(425441a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  910): releaseWL(42345920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/fb4a(:<default>):UserScope( 4525): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=33 [3][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 271
D/libc    (  365): [NET]res_nsend:resplen=84
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2228): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2228): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4525): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=6 [16][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(42533be0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1409 10028 null
,D/PMS     (  910): releaseWL(42533be0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2228/10028)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.gms (2228/10028)
,W/GLSUser ( 1409): GoogleAccountDataService.getToken()
,W/GLSActivity( 1409): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1409): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1409): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2228): awaiting user notification for token
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/PMS     (  910): releaseWL(42b70108): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41d296f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1119): com.google.android.gms 1 7 2 12
,I/CheckinTask( 2228): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2228): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/GCM     ( 1409): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  910): releaseWL(43554808): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/GCM     ( 1409): GCM config loaded
,E/ActivityThread( 2228): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41aa5f58 that was originally bound here
E/ActivityThread( 2228): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41aa5f58 that was originally bound here
E/ActivityThread( 2228): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2228): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2228): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2228): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2228): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2228): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2228): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2228): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2228): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2228): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2228): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2228): 	at bks.a(SourceFile:298)
E/ActivityThread( 2228): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2228): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2228): 	at java.lang.Thread.run(Thread.java:864)
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3dcb +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175,
I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420eb570
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
I/PMS     (  910): Going to sleep due to screen timeout...
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  910): setLight #0: color=#0
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420eb570, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420153b8
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@41b4acd0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 372ms
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
D/PMS     (  910): OOBE c monitor 11
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
I/InputMethodManagerService(  910): Disable input method client, pid=4454
D/PMS     (  910): acquireWL(43a153d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425b2de0)
D/PMS     (  910): releaseWL(43a153d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  910): acquireWL(42499cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(42499cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  910): wakingUp
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
I/WindowManager(  910): No lock screen! windowToken=null
D/PMN     (  910): onScreenOn
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2382): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1256): applyRouting - 0
,D/MtpService( 2382): [MTP][onReceive]-
D/HtcPowerSaver(  910): updateBatteryInfo
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/NfcService( 1256): applyRouting -2
,D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON,
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19609 delay=15s
D/PMS     (  910): acquireWL(43464e20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  910): releaseWL(43464e20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): SET_SCREEN_ON:On
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1119): stop update clock
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4706 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,V/SRS_Proc(  373): ParamSet string: screen_state=on
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  910): updateScreenOn: false
,W/ContextImpl( 4706): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4706): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(43c010e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4706 1000 null
,D/SmartSyncUtils( 4706): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1398): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  910): releaseWL(43c010e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  910): killProcessQuiet, pid=4345
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4345:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  910): Recipient 4345
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TetherSettings( 4229): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4229): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4229): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4229): Cust_ConnectToPC   : spcsc>false
D/        ( 4229): Cust_ConnectToPC   : IPT>true
,D/        ( 4229): Cust_ConnectToPC   : Singel_USB>false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOn: 1452520914113
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOn: 1452520914113
,W/Settings( 4229): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4229): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4229): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4229): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/PMS     (  910): acquireWL(4403c378): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1505 10028 null
,D/PMS     (  910): releaseWL(4403c378): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PSReceiver( 4229): onReceive:android.intent.action.USER_PRESENT
I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420153b8
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420153b8, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@41b4acd0
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SmartNS_PSService( 4229): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4229): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4229):  defaultType:0
W/ContextImpl( 4229): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(42ff7ed0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19609 mDataStallAlarmIntent=PendingIntent{43b4d6b8: PendingIntentRecord{424ac0b0 android broadcastIntent}}
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): SET_SCREEN_ON:Off
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1179): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  910):    returned true
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  373): ParamSet string: screen_state=off
D/PMS     (  910): acquireWL(435460e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
D/NetworkPolicy(  910): updateScreenOn: false
,W/ContextImpl( 4706): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
D/ContactMessageStore( 1245): Background delete complete
D/SmartSyncUtils( 4706): isEpsOn(), nState = 0
D/SmartSyncUtils( 4706): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4706): isEpsOn(), nState = 0
,D/WifiService(  910): New client listening to asynchronous messages
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(435460e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b4acd0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b4acd0, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b4acd0, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b4acd0
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41ec2850 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41ec2850 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOff
D/PMS     (  910): acquireWL(438f70b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1505 10028 null
D/PMS     (  910): releaseWL(438f70b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1398): service - mHandler: cancel location update
,D/AutoSetting( 1398): service -           changes count: 0
,I/GAV2    ( 4588): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(440260a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
,D/PMS     (  910): acquireWL(440e1388): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
,D/PMS     (  910): releaseWL(440260a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  910): releaseWL(440e1388): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{41c7fbc8 u0 com.test.thalitest/.MainActivity t2}
,I/jxcore-log( 4454): Test app app.js loaded
I/jxcore-log( 4454): 
,I/Choreographer( 4454): Skipped 536 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4454): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4454): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a8f368 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  910): releaseWL(42ff7ed0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4454): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  910): killProcessQuiet, pid=4368
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4368:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4368
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1489): service - handleMessage() stop self
,D/AutoSetting( 1489): service - onDestroy() END
,D/AutoSetting( 1489): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4386
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4386:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4386
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 11.005MB for 36946-byte allocation
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 11.035MB for 55414-byte allocation
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 11.041MB for 42972-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4525/10026)
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 11.068MB for 65480-byte allocation
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 11.075MB for 44212-byte allocation
,I/dalvikvm-heap( 4525): Grow heap (frag case) to 11.098MB for 57362-byte allocation
,D/libc    ( 4525): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4525): [NET] getaddrinfo-,err=8
D/libc    ( 4525): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4525): [NET] getaddrinfo-, 1
,D/libc    ( 4525): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f349 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 18
D/libc    (  365): [NET]res_nsend:resplen=93
D/libc    (  365): [NET]res_queryN: exit 3, ancount=3
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4525): [NET] getaddrinfo_proxy-, success
I/global  ( 4525): call createSocket() return a new socket.
D/libc    ( 4525): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4525): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4525): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4525): [NET] getaddrinfo-,err=8
,D/PMS     (  910): acquireWL(4368c598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=117231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4368c598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(429f0710): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4525 10026 null
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4525): I/O error closing connection
I/global  ( 4525): java.net.SocketException: Socket is closed
I/global  ( 4525): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4525): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4525): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4525): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4525): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4525): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4525): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4525): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4525): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4525): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4525): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4525): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4525): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4525): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4525): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4525): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4525): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4525): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4525): Removing a connection that never existed!
D/PMS     (  910): releaseWL(429f0710): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43bf6158 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(436aaaf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(436aaaf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100,
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1398): service - mHandler: update timezone
,D/AutoSetting( 1489): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1489): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1489): service - onCreate()
D/AutoSetting( 1489): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1489): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/AutoSetting( 1489): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/DotMatrix( 1572): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1489): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1489): service - mHandler: update timezone
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1489): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1489): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1489): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1489): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e21fd0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 7 3 11
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  910): acquireWL(43e5bfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{4227a498: PendingIntentRecord{42452a38 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141028, Int=0
D/PMS     (  910): acquireWL(440b9e78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
V/AlarmManager(  910): sending alarm PendingIntent{422b9970: PendingIntentRecord{422b5880 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141470, Int=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
,D/PMS     (  910): releaseWL(43e5bfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  910): acquireWL(42cbcf70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1409 10028 null
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e2c6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  910): releaseWL(42cbcf70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1398): service - handleMessage() stop self
,D/AutoSetting( 1398): service - onDestroy() END
,D/AutoSetting( 1398): service - handleMessage() quit looper
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 44
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS,
D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  910): killProcessQuiet, pid=3972
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3972:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3972
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): releaseWL(440b9e78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{436dc778 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1489): service - handleMessage() stop self
,D/AutoSetting( 1489): service - onDestroy() END
,D/AutoSetting( 1489): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4332
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  910): Killing 4332:com.htc.cs.dm/u0a98 (adj 15): empty #17
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  910): Recipient 4332
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(43c9c760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(43c9c760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(436c45e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=177231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(436c45e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(4369ed38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4369ed38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(43653160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{422de3d0: PendingIntentRecord{434ca738 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226784, Int=0
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4750 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{42352718: PendingIntentRecord{423526b8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452521023022, Int=10800000
,D/PMS     (  910): releaseWL(43653160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4750/10047)
,D/Process (  910): killProcessQuiet, pid=4403
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4403:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4403
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/PMS     (  910): acquireWL(430dda70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): acquireWL(430dc510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{42c68380: PendingIntentRecord{434ca738 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231370, Int=0
,D/PMS     (  910): releaseWL(430dda70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,D/PMS     (  910): releaseWL(430dc510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(42cfbf20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=237231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42cfbf20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42ca98a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(42ca98a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(425c3fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425c3fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42298260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=297231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42298260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4454): TAP version 13
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): # setup
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): # multiplex can send data
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): # teardown
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): ok 1 String should be length:200
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): # setup
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): # muxServerBridge,
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): # teardown,
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): server bridge: new client socket
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): client bridge: new client socket,
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): client bridge: socket closed,
I/jxcore-log( 4454): 
,D/PMS     (  910): acquireWL(42372120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(42372120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(422b7110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(422b7110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(423ee400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=357231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(423ee400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1409): GoogleAccountDataService.getToken()
,W/GLSActivity( 1409): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1409): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1409): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1409): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1409): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1409): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1409): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1409): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1409): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1409): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1409): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e3b270 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4172): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4172): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4172): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4172): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4172): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4172): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4172): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4172): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 11 3 12
,D/libc    ( 4172): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4172): [NET] getaddrinfo-,err=8
D/libc    ( 4172): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4172): [NET] getaddrinfo-, 1
,D/libc    ( 4172): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6cd7 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 204
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4172): [NET] getaddrinfo_proxy-, success
I/global  ( 4172): call createSocket() return a new socket.
D/libc    ( 4172): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4172): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4172): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4172): [NET] getaddrinfo-,err=8
,D/PMS     (  910): acquireWL(43e540d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(43e540d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(4257b458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{43172d98: PendingIntentRecord{43100050 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=411138, Int=300000
,D/PMS     (  910): releaseWL(4257b458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  910): acquireWL(4248d928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4248d928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(431aeb20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=417231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(431aeb20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(424de8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  910): n_update end
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(424de8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(4258b180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4258b180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4245fed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=477231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4245fed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(422c59c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(422c59c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(43545cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43545cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(424943f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=537231, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(424943f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(423ad170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(423ad170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(440b7980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440b7980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
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
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4311e2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=597231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4311e2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42bafbb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bafbb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1245): sku_id=99
,D/ContactMessageStore( 1245): start background delete task...
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  910): acquireWL(440393d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(440393d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(422f0388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=657231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(422f0388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42ca4180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42ca4180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42345c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{43172d98: PendingIntentRecord{43100050 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711138, Int=300000
,D/PMS     (  910): releaseWL(42345c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/Process (  910): killProcessQuiet, pid=4417
,I/ActivityManager(  910): Killing 4417:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4417
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(42434758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=717231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42434758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(424e6628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(424e6628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4367a9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(4367a9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42516ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=777231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42516ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(436879c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(436879c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4408e5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  910): sending alarm PendingIntent{41cea838: PendingIntentRecord{423ba3f8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785666, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{429e4ed8: PendingIntentRecord{42552370 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452521612578, Int=1800000
,D/PMS     (  910): acquireWL(43e53ef0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2228 10028 null
D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,D/PMS     (  910): releaseWL(4408e5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  910): acquireWL(43fb1b10): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(43e53ef0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 2228): Aggregate from 1452520910454 (log), 1452519812538 (data)
,D/PMS     (  910): releaseWL(43fb1b10): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  910): acquireWL(43431730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(43431730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43689598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=837230, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43689598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43cfd948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43cfd948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4318bd38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=897231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4318bd38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43047c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43047c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43bd7f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  910): releaseWL(43bd7f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43d090e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=957231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43d090e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42cd6050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(42cd6050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4405a298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10028}
,V/AlarmManager(  910): sending alarm PendingIntent{425379e8: PendingIntentRecord{423219a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1009041, Int=0
,D/PMS     (  910): acquireWL(43672e10): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1409 10028 null
,V/AlarmManager(  910): sending alarm PendingIntent{42345b10: PendingIntentRecord{42441c68 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452521743393, Int=900000
,V/AlarmManager(  910): sending alarm PendingIntent{42005a90: PendingIntentRecord{434cc638 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452521814178, Int=0
,D/PMS     (  910): releaseWL(43672e10): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  910): acquireWL(440d2ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1409 10028 null
,W/ContextImpl( 4706): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  910): releaseWL(440d2ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4706): call getInstance()
,D/SmartSyncUtils( 4706): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4706): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4706): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4706): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
D/PMS     (  910): releaseWL(4405a298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(430dd8f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4706 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4706): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4706): SettingOnTime = 1452549600000, randomSettingOnTime = 1452546008000
D/SmartSyncScreenOnOffTimeReceiver( 4706): SettingOffTime = 1452538800000, randomSettingOffTime = 1452541134000
D/SmartSyncScreenOnOffTimeReceiver( 4706): bDayMode = false
D/PMS     (  910): acquireWL(434360b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1409 10028 null
D/SmartSyncScreenOnOffTimeReceiver( 4706): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4706): bNightModeTurnOffOnce = false
D/PMS     (  910): releaseWL(430dd8f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/GCM     ( 1409): Message class mow
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1409/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
,D/PMS     (  910): releaseWL(434360b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  910): acquireWL(43f820c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1409 10028 null
,D/PMS     (  910): releaseWL(43f820c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=7 [287][22][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(4408f6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(4408f6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43f9a250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1017231, Int=0
,D/PMS     (  910): releaseWL(43f9a250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43f8cc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43f8cc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43a84f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(43a84f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4368d820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1077231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4368d820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4368b640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4368b640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43673238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1137231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43673238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4364c8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4364c8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(433f2120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(433f2120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(430542f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1197231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(430542f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4245af38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4245af38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(422dc618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(422dc618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(423c9e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1257231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(423c9e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(422ccdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(422ccdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4217cf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(4217cf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42347500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1317231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42347500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(41d62b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(41d62b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42d6e770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1377231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42d6e770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42420a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42420a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(423aac08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(423aac08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42469998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1437231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42469998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(421a1018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(421a1018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(424e9638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(424e9638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42406e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1497231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42406e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(429c76e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(429c76e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4238a8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1557231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4238a8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(430c3990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430c3990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4250c058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4250c058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42321118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1617231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42321118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(424e7780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(424e7780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43684e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1677231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43684e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(425fc3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425fc3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(424597a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1737230, Int=0
,D/PMS     (  910): releaseWL(424597a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4369b660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  910): n_update end
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(4369b660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(423afb38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(423afb38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43616870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1797231, Int=0
,D/PMS     (  910): releaseWL(43616870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(44059dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(44059dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(44031ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(44031ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/ProcessStatsService(  910): Prepared write state in 54ms
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2016-01-10-21-45-07.bin
,D/PMS     (  910): acquireWL(44069068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422daf28: PendingIntentRecord{422e0000 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1857231, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44069068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(424b8758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(424b8758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4822): Error opening trace file: No such file or directory (2)
D/PMS     (  910): acquireWL(43f36200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
D/Process (  910): killProcessQuiet, pid=4588
I/ActivityManager(  910): Killing 4588:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  910): sending alarm PendingIntent{41cea838: PendingIntentRecord{423ba3f8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1529832, Int=0
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  910): killProcessQuiet, pid=4571
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  910): killProcessQuiet, pid=4555
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  910): killProcessQuiet, pid=3950
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  910): killProcessQuiet, pid=4511
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  910): killProcessQuiet, pid=4172
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  910): killProcessQuiet, pid=4081
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  910): Killing 4571:com.android.chrome/u0a96 (adj 15): empty for 1802s
D/ConnectivityService(  910): Done.
D/ConnectivityService(  910): Setting timer for 720seconds
I/ActivityManager(  910): Killing 4555:com.google.android.setupwizard/u0a78 (adj 15): empty for 1802s
I/ActivityManager(  910): Killing 3950:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
I/ActivityManager(  910): Killing 4511:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
I/ActivityManager(  910): Killing 4172:com.android.vending/u0a73 (adj 15): empty for 1823s
I/ActivityManager(  910): Killing 4081:com.google.android.gm/u0a107 (adj 15): empty for 1836s
V/AlarmManager(  910): sending alarm PendingIntent{42327de0: PendingIntentRecord{4247a550 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820621, Int=1800000
D/PMS     (  910): acquireWL(4365d028): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
V/AlarmManager(  910): sending alarm PendingIntent{4342dbb8: PendingIntentRecord{423219a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1911498, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{42345b10: PendingIntentRecord{42441c68 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452522643393, Int=900000
D/PMS     (  910): releaseWL(4365d028): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  910): acquireWL(43f69328): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1409 10028 null
D/PMS     (  910): releaseWL(43f69328): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
I/ActivityManager(  910): Recipient 4588
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4555
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4081
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4511
D/MediaRouterService(  910): Client com.google.android.music (pid 3950): Died!
I/ActivityManager(  910): Recipient 4571
I/ActivityManager(  910): Recipient 3950
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4172
D/PMS     (  910): acquireWL(43792c18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1409 10028 null
D/PMS     (  910): releaseWL(43792c18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/ContextImpl( 4706): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  910): releaseWL(43f36200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BatSI   (  910): Couldn't get kernel wake lock stats
D/GCM     ( 1409): Message class mow
D/PMS     (  910): acquireWL(4317b460): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1409 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1409/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1409/10028)
D/PMS     (  910): releaseWL(4317b460): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  910): acquireWL(4259a718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1409 10028 null
D/PMS     (  910): releaseWL(4259a718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/BatSI   (  910): Couldn't get kernel wake lock stats
D/CustomizationManager( 4822): ====startRecUseTime====
D/htc.customization.log.level( 4822):  is 
W/CustomizationLogLevel( 4822): Level value is invalid, use default level 2
W/BatSI   (  910): Couldn't get kernel wake lock stats
D/CustomizationManager( 4822):  Read ACC file spent 0.083 (s)
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4822): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4822): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4822): Parsing tag category name = system
I/CustomizationCIDLoader( 4822): Parsing tag category name = application
I/CustomizationCIDLoader( 4822): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4822): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4822): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4822): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4822): Parsing tag category name = Settings
D/CustomizationManager( 4822):  Read CID file spent 0.139 (s)
D/CustomizationManager( 4822):  All configurations done spent 0.139 (s)
W/HtcNativeFlag( 4822): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4822): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4822): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4822): Fail to get flag for type 'language', use default value: -1
W/BatSI   (  910): Couldn't get kernel wake lock stats
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4822, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  910): killProcessQuiet, pid=4454
I/ActivityManager(  910): Killing 4454:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  910):   Force finishing activity ActivityRecord{41c7fbc8 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  910): Copying FileAsset 0x69f5edc0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/InputDispatcher(  910): channel '423f02c0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  910): channel '423f02c0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  910): Attempted to unregister already unregistered input channel '423f02c0 com.test.thalitest.MainActivity (s)'
I/WindowManager(  910): WINDOW DIED Window{423f02c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  910): Client connection lost with reason: 4
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WindowManager(  910): Failed looking up window
W/WindowManager(  910): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42533048 does not exist
W/WindowManager(  910): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  910): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  910): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  910): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  910): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  910): WIN DEATH: null
W/PackageSettings(  910): Skipping PackageSetting{42171f88 com.example.hello/10356} due to missing metadata
W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4454 uid 10348
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
I/dalvikvm-heap( 4208): Grow heap (frag case) to 15.212MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/acms    ( 1877): Unregistering com.test.thalitest
D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
E/acms    ( 1877): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1505): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): acquireWL(435541b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1505 10028 null
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  910): releaseWL(435541b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1334): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1334): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=7 [162][12][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/AccTypeManager( 1334): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PackageBroadcastService( 2228): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  910): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4843 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
E/ExternalAccountType( 1334): Unsupported attribute readOnly
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  910): Delaying start of: ServiceRecord{440223e8 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4843): install
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PeopleContactsSync( 2228): CP2 sync disabled
I/MultiDex( 4843): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4843): loading existing secondary dex files
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/MultiDex( 4843): load found 1 secondary dex files
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/MultiDex( 4843): install done
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2228, uid=10028, userID:0
I/Icing   ( 2228): doRemovePackageData com.test.thalitest
D/PMS     (  910): acquireWL(4250a7c0): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
D/PMS     (  910): releaseWL(4250a7c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  910): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4862 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4843): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  910): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4862): install
I/MultiDex( 4862): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4862): loading existing secondary dex files
I/MultiDex( 4862): load found 1 secondary dex files
I/MultiDex( 4862): install done
I/ProviderInstaller( 4862): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  910): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1398): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1398): handle notify Blinkfeed plugin client changed
I/ActivityManager(  910): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4880 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  910): killProcessQuiet, pid=4208
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4208:com.google.android.apps.plus/u0a160 (adj 15): empty for 1804s
I/ActivityManager(  910): Recipient 4208
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4843): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4843): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4843): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4843): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4843): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4843): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4843): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4843): threadid=12: thread exiting with uncaught exception (group=0x4164fe30)
E/AndroidRuntime( 4843): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4843): Process: com.google.android.gms.drive, PID: 4843
E/AndroidRuntime( 4843): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4843): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4843): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4843): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4843): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4843): 	at ctn.run(SourceFile:985)
E/ActivityManager(  910): App crashed! Process: com.google.android.gms.drive
D/Process ( 4843): killProcess, pid=4843
D/Process ( 4843): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4843
I/ActivityManager(  910): Process com.google.android.gms.drive (pid 4843) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
E/DropBoxManagerService(  910): Can't write: system_app_crash
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
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4880, uid=10073, userID:0
D/Finsky  ( 4880): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4880/10073)
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4880/10073)
D/Finsky  ( 4880): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 4880): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4880): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4880): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4880): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4880): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4880): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4880): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4880): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4880): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4880): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4880): threadid=25: thread exiting with uncaught exception (group=0x4164fe30)
E/ActivityManager(  910): App crashed! Process: com.android.vending
E/AndroidRuntime( 4880): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4880): Process: com.android.vending, PID: 4880
E/AndroidRuntime( 4880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4880): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4880): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4880): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4880): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4880): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4880): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4880): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4880, uid=10073, userID:0
D/Process (  910): killProcessQuiet, pid=4229
I/ActivityManager(  910): Killing 4229:com.android.settings/1000 (adj 15): empty for 1802s
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4880): killProcess, pid=4880
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4880): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2915): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4915 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  910): Recipient 4229
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Recipient 4880
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.android.vending (pid 4880) has died.
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b12dd8 +
I/Prism.WidgetManager( 1273): onLoadItems() +
W/PackageManager(  910): Unable to load service info ResolveInfo{425f8bf0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteLog( 2915): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2915): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x635f34c8
W/dalvikvm( 2915): threadid=14: thread exiting with uncaught exception (group=0x4164fe30)
E/AndroidRuntime( 2915): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2915): Process: com.google.android.googlequicksearchbox:search, PID: 2915
E/AndroidRuntime( 2915): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2915): 	at cid.d(PG:186)
E/AndroidRuntime( 2915): 	at clo.g(PG:594)
E/AndroidRuntime( 2915): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2915): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2915): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2915): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2915): 	at clr.tL(PG:827)
E/AndroidRuntime( 2915): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2915): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2915): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2915): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  910): App crashed! Process: com.google.android.googlequicksearchbox:search
I/TrimMemoryManager( 1273): [trimMemory] 5
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
D/Process ( 2915): killProcess, pid=2915
D/Process ( 2915): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  910): Recipient 2915
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.googlequicksearchbox:search (pid 2915) has died.
D/MediaRouterService(  910): Client com.google.android.googlequicksearchbox (pid 2915): Died!
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/WifiService(  910): Client connection lost with reason: 4
E/SQLiteDatabase( 4915): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4915): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4915): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4915): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4915): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4915): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4915): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4915): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4915): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4915): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4915): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4915): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4915): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4915): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4915): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4915): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4915): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4915): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4915): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4915): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4915): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4915): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4915): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4915): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4915): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4915): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4915): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4915): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4915): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4915): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4915): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4915): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4915): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4915): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4915): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4915): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4915): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4915): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4915): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4915): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4915): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4915): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4915): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4915): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4915): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4915): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4915): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4915): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4915): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4915): threadid=11: thread exiting with uncaught exception (group=0x4164fe30)
E/AndroidRuntime( 4915): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4915): Process: com.google.android.apps.docs, PID: 4915
E/AndroidRuntime( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4915): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4915): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4915): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4915): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4915): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
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
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4931 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4915): killProcess, pid=4915
D/Process ( 4915): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Recipient 4915
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4915) has died.

```
