#### Test 5615109319b4771_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  905): Waited long enough for: ServiceRecord{4260b3d0 u0 com.htc.htclocationservice/.AutoSettingService}
V/LightsService(  905): setLight #0: color=#26
V/LightsService(  905): setLight #0: color=#23
V/LightsService(  905): setLight #0: color=#1c
V/LightsService(  905): setLight #0: color=#15
V/LightsService(  905): setLight #0: color=#14
,--------- beginning of /dev/log/main
E/cutils-trace( 4465): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4465): ====startRecUseTime====
D/htc.customization.log.level( 4465):  is 
W/CustomizationLogLevel( 4465): Level value is invalid, use default level 2
D/CustomizationManager( 4465):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4465): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4465): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4465): Parsing tag category name = system
I/CustomizationCIDLoader( 4465): Parsing tag category name = application
I/CustomizationCIDLoader( 4465): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4465): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4465): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4465): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4465): Parsing tag category name = Settings
D/CustomizationManager( 4465):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4465):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 4465): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4465): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4465): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4465): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4465
D/PMS     (  905): acquireHCC(42680aa8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(4241bd98): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x66612ed0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1112216008
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b83458
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  905): acquireWL(42338770): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4476 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4476): Copying FileAsset 0x5c725428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4476): Binding Chromium to main looper Looper (main, tid 1) {41a96ea8}
I/LibraryLoader( 4476): Expected native library version number "",actual native library version number ""
I/chromium( 4476): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4476): Initializing chromium process, renderers=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425b1088:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4476): 1101728872: getState(). Returning 12
D/PMS     (  905): acquireWL(41a96c40): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  905): acquireWL(426cc7e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  905): releaseWL(41a96c40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4476): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4476): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4476): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4476): Local Branch: 
I/Adreno-EGL( 4476): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4476): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4476):                  aa63bbd948f41d15fc72f585e
W/chromium( 4476): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4476): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4476): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4476): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4476): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4476): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4476): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4476): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4476): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4476): CordovaWebView is running on device made by: HTC
,W/AwContents( 4476): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1273
,W/ResourceType( 4476): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManagerService(  905): Enable input method client, pid=4476
I/InputMethodManager( 4476): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ae2318, mServedView=org.apache.cordova.engine.SystemWebView{41aa7f80 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4476): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +262ms
D/PMS     (  905): releaseWL(42338770): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4476): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4476): JniHelper::setJavaVM(0x41574048), pthread_self() = 1663517616
,D/JX-Cordova( 4476): jxcore cordova android initializing
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 11.994MB for 42652-byte allocation
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 12.071MB for 95956-byte allocation
,I/SensorManager(  905): mEventCount = 1051
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 12.150MB for 143930-byte allocation
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 12.265MB for 215890-byte allocation
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 12.440MB for 323830-byte allocation
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 12.711MB for 485740-byte allocation
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 13.687MB for 1092904-byte allocation
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 14.632MB for 1639352-byte allocation
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 15.878MB for 2459024-byte allocation
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 18.063MB for 3688532-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(42680aa8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(4241bd98): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4476): Initializing JXcore engine
,W/jxcore-log( 4476): JXcore engine is ready
,W/jxcore-log( 4476): Starting JXcore engine
,W/jxcore-log( 4476): Platform android
W/jxcore-log( 4476): 
,W/jxcore-log( 4476): Process ARCH arm
W/jxcore-log( 4476): 
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  905): releaseWL(426cc7e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4476): JXcore Cordova bridge is ready!
I/jxcore-log( 4476): 
,W/jxcore-log( 4476): JXcore engine is started
,I/chromium( 4476): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4476): Toggling radios to true
I/jxcore-log( 4476): 
,D/BluetoothAdapter( 4476): enable(): BT is already enabled..!
,D/WifiManager( 4476): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 916
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
D/WifiManager( 4476): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
,D/WifiManager( 4476): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): TDLS: Tear down peers
,I/wpa_supplicant( 1177): wpa_driver_nl80211_disconnect(reason_code=3),
,I/jxcore-log( 4476): Radios toggled,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): My device name is: HTC-HTC Desire 820,
I/jxcore-log( 4476): 
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4476, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1177): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1177): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1177): TDLS: Remove peers on disassociation
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7848bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1177):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1177): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1177): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (0)+
D/Tethering(  905): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1177): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48,
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412,
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3,
D/WifiPerfLock(  905): release()
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(434a66c8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
,D/DhcpStateMachine(  905): [RunningState] Stop DHCP
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  905): doBoolean: RECONNECT
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19493 mDataStallAlarmIntent=PendingIntent{431fa230: PendingIntentRecord{4240ecf0 android broadcastIntent}}
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): Fast associate: Old scan results
I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  905):    returned true
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
D/WISPrService( 3825): >>>>>WISPrService start isConnected = false<<<<<
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
D/WifiP2pService(  905): InactiveState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
D/WifiP2pService(  905): P2pEnabledState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
D/UsbnetStateTracker(  905): isAvailable+-
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WISPrService( 3825): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/WifiService(  905): New client listening to asynchronous messages
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
,D/ConnectivityService(  905): resetConnections(wlan0, 3)
V/NativeCrypto( 2857): Read error: ssl=0x5ca1b8c0: I/O error during system call, Connection timed out
D/WISPrService( 3825): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3825): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] entry_id:3   entry:0xb8139320  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8138fd8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8139428  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb8139240  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb81390e8  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8134f60  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,V/NativeCrypto( 2857): SSL shutdown failed: ssl=0x5ca1b8c0: I/O error during system call, Broken pipe
D/PMS     (  905): acquireWL(423ca708): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  905): acquireWL(425e7e08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/WifiNative-wlan0(  905): doBoolean: SCAN
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (2857/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  905): releaseWL(423ca708): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,D/PMS     (  905): releaseWL(425e7e08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43265b18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(43265b18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1602/10029)
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3889): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3889/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1959/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4531 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4531): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4531): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4531): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4531): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4531): Preparing secondary program dexes.
V/DexLibLoader( 4531): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4531): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4531): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4531): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4531): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4531): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4531): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4531): Dex already copied
D/OdexVerifier( 4531): Odex verification is skipped.
,V/DexLibLoader( 4531): Creating class loader
,V/DexLibLoader( 4531): Finished creating class loader,
V/DexLibLoader( 4531): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4531): Dex already copied
D/OdexVerifier( 4531): Odex verification is skipped.
,V/DexLibLoader( 4531): Creating class loader,
V/DexLibLoader( 4531): Finished creating class loader,
V/DexLibLoader( 4531): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4531): Dex already copied
D/OdexVerifier( 4531): Odex verification is skipped.
,V/DexLibLoader( 4531): Creating class loader,
,V/DexLibLoader( 4531): Finished creating class loader
V/DexLibLoader( 4531): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4531): Dex already copied
D/OdexVerifier( 4531): Odex verification is skipped.,
V/DexLibLoader( 4531): Creating class loader
V/DexLibLoader( 4531): Finished creating class loader
V/DexLibLoader( 4531): Verifying classes from secondary dexes.
D/DexLibLoader( 4531): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4531): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4531): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4531): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4531): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4531): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4531): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4531): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4531): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1177): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1177): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1177): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1177): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1177): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1177): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 3
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 1
I/wpa_supplicant( 1177): wpa_s->is_screen_on 1
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): selected network = 1
D/wpa_supplicant( 1177): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb784a4e8  current_ssid=0x0
D/wpa_supplicant( 1177): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): supplicant attached completed, trigg,er assoc.
D/wpa_supplicant( 1177): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1177): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1177): check if in concurrent case
I/wpa_supplicant( 1177): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1177): RSN: PMKSA cache search - network_ctx=0xb784a4e8 try_opportunistic=0
D/wpa_supplicant( 1177): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1177): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1177): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1177): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1177): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1177): nl80211: Unsubscribe mgmt frames handle 0xb7849718 (mode change)
D/wpa_supplicant( 1177): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7849718
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb7849718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1177):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1177):   * freq=2412
D/wpa_supplicant( 1177):   * Auth Type 0
D/wpa_supplicant( 1177):   * WPA Versions 0x2
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1177): nl80211: Connect request send successfully
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:0,0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1177): reply (636) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-46
I/wpa_supplicant( 1177): tsf=0000000106041483
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-52
I/wpa_supplicant( 1177): tsf=0000000106041503
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=2
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-78
I/wpa_supplicant( 1177): tsf=0000000021410941
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-52
I/wpa_supplicant( 1177): tsf=0000000106041498
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=4
I/wpa_supplicant( 1177): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1177): freq=2437
I/wpa_supplicant( 1177): level=-92
I/wpa_supplicant( 1177): tsf=0000000106041512
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=UPC4688432
I/wpa_supplicant( 1177): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 106041483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 106041503, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 21410941, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 106041498, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 106041512, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/dalvikvm( 4531): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4531): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4531): Verify
,D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1177): nl80211: Connect event
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1177): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1177): Add randomness: count=11 entropy=5
I/wpa_supplicant( 1177): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1177): TDLS: Remove peers on association
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1177): EAPOL: enable timer tick
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1177): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1177): Get randomness: len=32 entropy=6
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/wpa_supplicant( 1177): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb78499f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1177):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1177): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f02b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1177):    broadcast key
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1177): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1177): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1177): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1177): wlan0: Connect to SSID: NG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=6
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): set send_ind_to_ndc = 0
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1177): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1177): EAPOL authentication completed successfully
I/wpa_supplicant( 1177): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/Tethering(  905): [isWifi] getHotspotEnabled: f,alse
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WISPrService( 3825): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3825): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [2][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 1
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true,
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1,
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(425b2738): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
,D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiNative-wlan0(  905):    returned null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4250e028 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4250e028 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiService(  905): New client listening to asynchronous messages
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422066c8
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422066c8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e4d290
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@425c2640
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  905): mWirelessDisplayManager is null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4531): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4531): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4531): Grow heap (frag case) to 9.508MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4158
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4158:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AutoSetting( 1345): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4551 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1345/10055)
,D/AutoSetting( 1345): Util - no network available!
D/AutoSetting( 1345): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1345): service - mHandler: cancel location update
,D/AutoSetting( 1345): service -           changes count: 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1345/10055)
,I/ActivityManager(  905): Recipient 4158
,W/fb4a(:<default>):UserScope( 4531): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4531): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4531): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 315ms
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425f6e18)
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
D/PMS     (  905): nativeSetInteractive:false
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
D/PMN     (  905): wakingUp
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4476
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
,D/NfcService( 1255): applyRouting -2
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): acquireWL(4260bdf0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  905): releaseWL(4260bdf0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  905): acquireWL(43d99500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMN     (  905): onScreenOn
,D/PMS     (  905): releaseWL(43d99500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,D/MtpService( 1959): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1959): [MTP][onReceive]-
,D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): acquireWL(43782768): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/MobileConnectivityChangeReceiver( 4551): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4551): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4551): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4551): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/PMS     (  905): releaseWL(43782768): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1115): stop update clock
I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4580 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4272
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/dalvikvm( 4531): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4531): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:On
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (1)+
E/dalvikvm( 4531): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4531): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
E/dalvikvm( 4531): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4531): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/ActivityManager(  905): Killing 4272:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4551/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4551/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4551/10079)
E/dalvikvm( 4531): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4531): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
W/dalvikvm( 4531): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4531): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4531): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
W/dalvikvm( 4531): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4531): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4531): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4531): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4531): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4531): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4531): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/ActivityManager(  905): Recipient 4272
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/SRS_Proc(  373): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  905): updateScreenOn: false
,I/dalvikvm-heap( 4531): Grow heap (frag case) to 9.913MB for 39954-byte allocation
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4594 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4304
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4304:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/dalvikvm-heap( 4531): Grow heap (frag case) to 9.989MB for 79892-byte allocation
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  905): Recipient 4304
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): acquireWL(4383d1c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4383d1c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(436f0568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(436f0568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1743): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): onScreenOn: 1453044821959
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1743): onScreenOn: 1453044821959
,I/dalvikvm-heap( 4531): Grow heap (frag case) to 10.061MB for 84664-byte allocation
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e4d290
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e4d290, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@425c2640
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(439479a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4594): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4594): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4594): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4594): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4531): Grow heap (frag case) to 10.088MB for 28144-byte allocation
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4594): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 4476): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4476): 
,I/dalvikvm-heap( 4531): Grow heap (frag case) to 10.276MB for 75760-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4594/10151)
,V/WebViewChromiumFactoryProvider( 4594): Binding Chromium to main looper Looper (main, tid 1) {41a9efe0}
,I/LibraryLoader( 4594): Expected native library version number "",actual native library version number ""
,I/chromium( 4594): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4594): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4594): BLUETOOTH permission is missing!
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/PMS     (  905): acquireWL(42c47c48): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  905): acquireWL(42c5aca0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  905): releaseWL(42c5aca0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441d1638 u0 ReceiverList{441d1518 4531 com.facebook.katana/10027/u0 remote:42c5acd0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441d1638 u0 ReceiverList{441d1518 4531 com.facebook.katana/10027/u0 remote:42c5acd0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e50100 u0 ReceiverList{43e500a0 4531 com.facebook.katana/10027/u0 remote:43b7d400}}
,I/Adreno-EGL( 4594): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG (),
I/Adreno-EGL( 4594): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4594): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4594): Local Branch: 
I/Adreno-EGL( 4594): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4594): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
,I/Adreno-EGL( 4594):                  aa63bbd948f41d15fc72f585e
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
,I/NSApplication( 4594): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4594/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4594/10151)
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19494 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:Off
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1177): get_ip_address source addr = 02000000
I/wpa_supplicant( 1177): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/PMS     (  905): acquireWL(42e41e40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(42e41e40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  373): ParamSet string: screen_state=off
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
D/Process (  905): killProcessQuiet, pid=4327
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4065/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4065/10160)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
I/ActivityManager(  905): Killing 4327:com.htc.backup/1000 (adj 15): empty #17
,I/iu.Environment( 2164): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/NetworkPolicy(  905): updateScreenOn: false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
I/iu.UploadsManager( 2164): num queued entries: 0
I/iu.UploadsManager( 2164): num updated entries: 0
I/iu.SyncManager( 2164): NEXT; no task
D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
I/ActivityManager(  905): Recipient 4327
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): acquireWL(4330b6f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
,D/AutoSetting( 1345): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  905): releaseWL(4330b6f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/AutoSetting( 1345): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3825): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3825): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3825): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3825): Cust_ConnectToPC   : spcsc>false
D/        ( 3825): Cust_ConnectToPC   : IPT>true
D/        ( 3825): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3825): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3825): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3825): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3825): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3825): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3825): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3825): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3825):  defaultType:0
D/wpa_supplicant( 1177): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1177): EAPOL: disable timer tick
W/ContextImpl( 3825): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4531): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/AutoSetting( 1345): service - mHandler: cancel location update
,D/AutoSetting( 1345): service -           changes count: 0
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4531): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] getTotalRam: 1873 Mb
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4531): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4639 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  905): acquireWL(442f71c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(442f71c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4428af78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4428af78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1743): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1743): onScreenOff
W/ActivityManager(  905): Activity pause timeout for ActivityRecord{4235c490 u0 com.test.thalitest/.MainActivity t2}
,W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4639): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(425c8048): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4639 1000 null
,D/SmartSyncUtils( 4639): getMobilePolicyEnabled, result = true
D/PMS     (  905): releaseWL(425c8048): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Process (  905): killProcessQuiet, pid=4291
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Killing 4291:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4291
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4639): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4639): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4639): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425c2640
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425c2640, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425c2640, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425c2640
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425c2b88 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425c2b88 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
,I/jxcore-log( 4476): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4476): 
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(425b2738): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  905): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1177): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
,D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  905): WAN detection
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/ConnectivityService(  905): Provision feature enable=false
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3825): >>>>>WISPrService start isConnected = true<<<<<
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
,D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@42425a30
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
D/PMS     (  905): acquireWL(43ab5020): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4551/10079)
I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  905): acquireWL(4392c220): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2164 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2164): Checkin interval check for package: unspecified last checkin: 1453044773411 min interval config: 0 actual interval: 49704
D/PMS     (  905): acquireWL(4388d9b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2164 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4392c220): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2164): Checking schedule, now: 1453044823123 next: 1453044803374
,I/CheckinService( 2164): active receiver: enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2164, uid=10029, userID:0
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
I/CheckinService( 2164): Preparing to send checkin request
I/EventLogService( 2164): Accumulating logs since 1453044769356
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43ab5020): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2164): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2164): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 4476): Test app app.js loaded
I/jxcore-log( 4476): 
,I/Choreographer( 4476): Skipped 271 frames!  The application may be doing too much work on its main thread.
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2164/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,W/ResourceType( 4476): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4476): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aa7f80 VFEDH.C. .F....ID 0,0-720,1134 #64}
,V/GLSActivity( 2857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  905): releaseWL(439479a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
V/GLSActivity( 2857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/chromium( 4476): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4693 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4693): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4693): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4693): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4693): install
,I/MultiDex( 4693): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4693): loading existing secondary dex files
,I/MultiDex( 4693): load found 3 secondary dex files
,I/MultiDex( 4693): install done
,W/dalvikvm( 4693): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4693): VFY: unable to resolve instance field 36
,W/dalvikvm( 4693): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4693): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4693): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4693): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4693): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,W/dalvikvm( 4693): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4693): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4693): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4693): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/LocationInitializer( 2164): Restart initialization of location
,W/dalvikvm( 4693): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/MDM     ( 1223): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 2857): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2857): Proximity feature is not enabled.
,V/GLSActivity( 2857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  905): acquireWL(42e580b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42e580b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,I/WVCdm   (  373): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  373): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  373): CdmEngine::OpenSession
,I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4693): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  373): PrepareKeyRequest: nonce=1890414264
,I/WVCdm   (  373): CdmEngine::CloseSession
,D/PMS     (  905): releaseWL(434a66c8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(42563490): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): releaseWL(42563490): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1602/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
,I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,D/CaptivePortalTracker(  905): NoActiveNetworkState
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3889/10154)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4551/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/NetworkMonitor( 3889): type=WIFI subType= reason=null isConnected=true
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3941/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(428d67f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1602/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
D/PMS     (  905): releaseWL(428d67f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1959/10021)
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1345): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4551): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4551): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1345/10055)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4594/10151)
D/AutoSetting( 1345): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1345): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1345): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1345): service - onStartCommand() check timezone in 30000
,W/Settings( 4693): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1345/10055)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4065/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4065/10160)
,D/PMS     (  905): acquireWL(442114f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2164 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2164): Checkin interval check for package: unspecified last checkin: 1453044773411 min interval config: 0 actual interval: 50800
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(442114f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 13.518MB for 1821008-byte allocation
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2164, uid=10029, userID:0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2164): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2164): num queued entries: 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
I/iu.UploadsManager( 2164): num updated entries: 0
I/iu.SyncManager( 2164): NEXT; no task
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/libc    ( 2857): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 2857): [NET] getaddrinfo-,err=8
D/libc    ( 2857): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 2857): [NET] getaddrinfo-, 1
,D/libc    ( 2857): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4eb5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/PMS     (  905): acquireWL(42656798): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 243
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2857): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
,W/fb4a(:<default>):UserScope( 4531): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4531): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    ( 2857): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 2857): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
,D/libc    ( 2857): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 2857): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
,I/Adreno-EGL( 4693): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4693): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4693): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4693): Local Branch: 
I/Adreno-EGL( 4693): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4693): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4693):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  373): CdmEngine::OpenSession
,I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,E/fb4a(:<default>):LocalFbBroadcastManager( 4531): Called registerBroadcastReceiver twice.
D/PMS     (  905): acquireWL(4376ef20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/PMS     (  905): releaseWL(42656798): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2857/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/PMS     (  905): releaseWL(4376ef20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43413948): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2857/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2857/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
D/PMS     (  905): releaseWL(43413948): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/WVCdm   (  373): PrepareKeyRequest: nonce=1208329377
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4531/10027)
,I/WVCdm   (  373): CdmEngine::CloseSession
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4693/10029)
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
,I/CheckinRequestBuilder( 2164): Classify the device as Phone.
,D/libc    ( 2164): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2164): [NET] getaddrinfo-,err=8
D/libc    ( 2164): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2164): [NET] getaddrinfo-, 1
,D/libc    ( 2164): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =17bd +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 123
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2164): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2164): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2164): [NET] getaddrinfo-,err=8
,D/libc    ( 2164): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2164): [NET] getaddrinfo-,err=8
D/libc    ( 2164): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2164): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [15][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/CheckinTask( 2164): Sending checkin request (12076 bytes)
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(42c47c48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,I/CheckinRequestBuilder( 2164): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2164): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2164/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=6 [16][1][0]
,I/CheckinRequestBuilder( 2164): Classify the device as Phone.
,I/CheckinTask( 2164): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2164): Checking schedule, now: 1453044826008 next: 1453567763001
,I/CheckinService( 2164): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2164, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,I/CheckinService( 2164): Checking schedule, now: 1453044826035 next: 1453567763001
,I/CheckinService( 2164): active receiver: disabled
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2164, uid=10029, userID:0
D/libc    (  365): [NET] +++++ res_nsend xid =ac98 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/CheckinService( 2164): Recording last checkin time for package unspecified as 1453044826045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(4388d9b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2164/10029)
D/GCM     ( 2857): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4594): Thread[GAThread,5,main]: No campaign data found.
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1522): service - handleMessage() stop self
,D/AutoSetting( 1522): service - onDestroy() END
,D/AutoSetting( 1522): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4345
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4345:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4345
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=4379
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4379:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4379
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4743 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsUpdated
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
E/ExternalAccountType( 1331): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4743): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4743): MmsConfig.loadMmsSettings
,W/dalvikvm( 4743): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4743): VFY: unable to resolve instance field 36
,W/dalvikvm( 4743): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4743): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4766 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4743, uid=10111, userID:0
W/PackageManager(  905): Unable to load service info ResolveInfo{429a4ea0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
D/MessageFrequencyProvider( 4766): onCreate
,D/MmsCustomizationProvider( 4766): query uri: content://htc-mms-customization/mms-ua/ua_string
W/Settings( 4743): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/GetPrviateResource( 4766): GetPrviateResource
V/GetPrviateResource( 4766): GetPrviateResource
D/MmsCustomizationProvider( 4766): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4743): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4743): MmsConfig.loadFromDatabase
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4743, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4743, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4743, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4743, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4743, uid=10111, userID:0
E/Babel   ( 4743): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4743): MmsConfig.loadFromResources
,E/Babel   ( 4743): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4743): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  905): acquireWL(42c05710): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4743 10111 null
,I/[PluginManager]RegisterService( 1345): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1345): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2830): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  905): acquireWL(431711b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4065 10160 null
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(42e5faf8): PARTIAL_WAKE_LOCK  Icing 0x1 2164 10029 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 4743): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 4766): sense_version=6.0
,D/BTAccessoryUtil( 4766): createReceiver
,D/PMS     (  905): releaseWL(42e5faf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/dalvikvm-heap( 4065): Grow heap (frag case) to 15.218MB for 1821008-byte allocation
D/BTAccessoryUtil( 4766): registerReceiver return intent = null
D/MessageCustFlag( 4766): sku_id=99
,W/SystemReader( 4766): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  905): releaseWL(42c05710): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PMS     (  905): releaseWL(431711b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  905): acquireWL(42a62508): PARTIAL_WAKE_LOCK  Icing 0x1 2164 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
D/Messaging( 4766): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4766): networkCode: 
D/MessageCustFlag( 4766): sku_id=99
D/MmsConfig( 4766): SIE smsPri: null
D/MmsConfig( 4766): networkCode: 
,D/HtcTelephonyCapability( 4766): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4766): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4766): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4766): Cannot find qct_8960_interface, use default value instead
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.950MB for 1821008-byte allocation
,D/Process (  905): killProcessQuiet, pid=3863
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3863:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  905): Recipient 3863
,D/PackageBroadcastService( 2164): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2164): Null package name or gms related package.  Ignoreing.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 2164): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(441e43a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(441e43a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
,D/PMS     (  905): acquireWL(4321a0d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4321a0d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43704968): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43704968): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(445cdca8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(445cdca8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2830): UpdateCorporaTask done [took 495 ms] updated apps [took 495 ms] 
,D/Process (  905): killProcessQuiet, pid=3941
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3941:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3941
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fc38 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/Icing   ( 2164): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2164): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(42a62508): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fc38 -
,D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1245): -- N1 =0
,D/PhoneApp( 1245): -- N2 =0
,D/PhoneApp( 1245): -- N3 =0
,D/Messaging( 4766): mNeedToUpdateDate2 start
,D/MmsConfig( 4766): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4766): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4766): 
D/MmsAsyncWorkHandler( 4766): HM tk = 20001
,D/ReportIndicatorCache( 4766): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4766): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41aac330
,I/Messaging( 4766): mccmnc> 
D/DraftCache( 4766): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4766): [DraftCache/1] refresh
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1245):  phoneType = -1
D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4766): networkCode: 
,D/Messaging( 4766): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4766): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4766): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4766): createReceiver
,D/MessageCustFlag( 4766): sense_version=6.0
,D/Messaging( 4766): mNeedToUpdateDate2: false
,D/Jerry   ( 4766): start to preload cursor >>>>>>>
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1245):  phoneType = -1
D/TelephUtils( 1245): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,V/MmsProvider( 1245): Update uri=content://mms, match=0
,V/MmsProvider( 1245): selection=st=129 AND m_type!=134
,D/Messaging( 4766): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4766): TransactionService is going to be woken up.
D/Messaging( 4766): ViewCache CreatePreload
,D/Messaging( 4766): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4766): 1-Creating TransactionService
,D/Cust_MMSMS( 4766): _has_set_default_values_2=true
,V/TransactionService( 4766): onStartCommand: 1
,D/MmsSystemEventReceiver( 4766): unRegisterForConnectionStateChanges
V/TransactionService( 4766): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4766): Loading previous transactions.
,D/MsgPreferenceUtils( 4766): def_index: 0
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1245): device_type: 1
,D/MsgPreferenceUtils( 4766): globalIndex = 1
D/TransactionService( 4766): Force set service start id to 1
V/TransactionService( 4766): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4766): unRegisterForConnectionStateChanges
,D/TransactionService( 4766): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4766): Destroying TransactionService
D/MsgPreferenceUtils( 4766): phone state: true
D/MsgPreferenceUtils( 4766): sd state: false
D/MsgPreferenceUtils( 4766): vIndex = 0
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,V/TransactionService( 4766): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1245): sku_id=99
,D/DraftCache( 4766): [DraftCache/472] rebuildCache
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4766): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/Jerry   ( 1245): URI_DRAFT
,D/DraftCache( 4766): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4766): [DraftCache/472] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4766): 
D/MmsAsyncWorkHandler( 4766): HM tk = 20002
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1245): sku_id=99
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1245): sku_id=99
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4743): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  905): acquireWL(4259b860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=125021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4259b860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425a1ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/BatteryService(  905): n_update end
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(425a1ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(426a76d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{425cea88: PendingIntentRecord{429c5118 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126490, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{4236d610: PendingIntentRecord{42adc2d8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137500, Int=0
,D/PMS     (  905): acquireWL(42bc5050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [16][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42e8b068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42e8b068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42bc5050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
,D/PMS     (  905): acquireWL(43266168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426a76d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(43266168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43620b30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0],
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529,
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): acquireWL(4263f848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(424e2410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1453044852771 tag=VacuumService
,D/PMS     (  905): releaseWL(43620b30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4263f848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42490768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(42490768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4251e298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(424e2410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(4251e298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42c1d040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(42c1d040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42466f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0],
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(42466f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4265b978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): acquireWL(42531890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42531890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42619120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4265b978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43ec1580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(43ec1580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 10356 seconds from now (1453044853493)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f298 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 234
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1345): service - has update message, not stop
,D/AutoSetting( 1345): service - mHandler: update timezone
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1522): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1589): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1522): service - mHandler: update timezone
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1522): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1522): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b2b6f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 1 10 3 11
D/PMS     (  905): releaseWL(42619120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42c5af78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(42c5af78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425bc468): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(425bc468): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42674c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  905): sending alarm PendingIntent{423643e0: PendingIntentRecord{4246c788 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140968, Int=0
,D/PMS     (  905): acquireWL(437818f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(42674c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d76b +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(437818f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42e5e218 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  905): acquireWL(42ae15e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42ae15e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1345): service - handleMessage() stop self
,D/AutoSetting( 1345): service - handleMessage() quit looper
,D/AutoSetting( 1345): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=4403
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 4403:com.htc.calendar/u0a13 (adj 15): empty #17
D/AutoSetting( 1522): service - handleMessage() stop self,
,I/ActivityManager(  905): Recipient 4403
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1522): service - onDestroy() END
,D/AutoSetting( 1522): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4417
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4417:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4417
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(4266b910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=185021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4266b910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426249e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426249e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(431effd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(431effd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42a24480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{426a8aa0: PendingIntentRecord{43b1ce50 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227223, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4850 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{423c5890: PendingIntentRecord{4261fa50 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453044926430, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{42c28dd8: PendingIntentRecord{43b1ce50 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227230, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42c3a9b0: PendingIntentRecord{43959d10 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=227237, Int=120000
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/PMS     (  905): releaseWL(42a24480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4850/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,D/Process (  905): killProcessQuiet, pid=4138
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4138:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4138
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42af4058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=245021, Int=0
,D/PMS     (  905): releaseWL(42af4058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426533d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426533d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(442f78c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(442f78c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(436cd728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=305021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(436cd728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42624388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  905): releaseWL(42624388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4476): TAP version 13
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # multiplex can send data
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 1 String should be length:200,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # basic
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 2 sane
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # another,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 3 sane,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # successfully create a new pkcs12 file and return hash value,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 4 should be equal,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 5 null,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 6 (unnamed assert),
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 7 should be equal,
I/jxcore-log( 4476): 
I/jxcore-log( 4476): ok 8 should not throw
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 9 (unnamed assert)
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 10 (unnamed assert)
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 11 should not throw
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 12 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 13 should be equal,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 14 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # failed to get mobile documents path
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 15 should be equal,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 16 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 17 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 18 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #init should register the networkChanged event
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 19 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #startBroadcasting should throw on null device name
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 20 should throw,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #startBroadcasting should throw on empty string device name,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 21 should throw
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 22 should throw,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #startBroadcasting should throw on NaN port,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 23 should throw,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #startBroadcasting should throw on negative port,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 24 should throw,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #startBroadcasting should throw on too large port,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 25 should throw
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 26 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 27 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 28 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 29 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 30 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 31 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 32 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 33 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 34 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 35 should be equal,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 36 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 37 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 38 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 39 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 40 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # should call Mobile("Disconnect") without an error,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 41 should be equal,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 42 should be equal,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # should call Mobile("Disconnect") and handle an error,
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
,I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 43 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): ok 44 should be equal
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # setup
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4476): 
,I/jxcore-log( 4476): # teardown
I/jxcore-log( 4476): 
,W/dalvikvm( 4476): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4476): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4476): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4476): start: Peer ID: B4:CE:F6:AB:A4:6A, peer name: 1453045035384.4476
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4476): bind: Binding a new listener
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4476): initialize: My bluetooth address is B4:CE:F6:AB:A4:6A
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4476): verifyIdentityString: Identity string created: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"1453045035384.4476"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4476): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 4476): getBluetoothService(): entry
,W/BluetoothAdapter( 4476): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1624): SOCK FLAG = 0 ***********************
,I/bt-btif ( 1624): BTA_JvCreateRecordByUser
D/bt-btm  ( 1624): BTM_AllocateSCN
D/bt-sdp  ( 1624): SDP_CreateRecord ok, num_records:17
I/bt-btif ( 1624): BTA_JvRfcommStartServer
I/bt-btm  ( 1624): BTM_SEC_REG[19]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
,I/bt-btm  ( 1624):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4476): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4476): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4476): start: OK
,I/io.jxcore.node.ConnectionHelper( 4476): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4476): start: Peer ID: B4:CE:F6:AB:A4:6A, peer name: 1453045035384.4476
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4476): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4476): bind: Binding a new listener
,W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 4476): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
,W/dalvikvm( 4476): VFY: unable to resolve new-instance 427 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
W/dalvikvm( 4476): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 4476): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
E/dalvikvm( 4476): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
,W/dalvikvm( 4476): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
,W/dalvikvm( 4476): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 4476): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4476): VFY: unable to resolve virtual method 1808: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4476): VFY: unable to resolve virtual method 1809: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4476): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4476): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/dalvikvm( 4476): threadid=1: thread exiting with uncaught exception (group=0x4166ce30)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at android.os.Looper.loop(Looper.java:157)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4476): 	at dalvik.system.NativeStart.main(Native Method)
,D/Process (  905): killProcessQuiet, pid=4447
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4447:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4447
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42688808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): onReceive BATTERY_CHANGED
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42688808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43790e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=365021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43790e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425f8180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  905): n_update end
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/PMS     (  905): releaseWL(425f8180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42612530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42612530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(44229020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=425021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44229020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42e43198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  905): n_update end
D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42e43198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(441d2770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41ce7490: PendingIntentRecord{424964f0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=461026, Int=0
,D/PMS     (  905): acquireWL(43160418): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(441d2770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425f86a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=4 [206][10][0]
,D/PMS     (  905): acquireWL(43063268): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 905 1000 WorkSource{10160}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(429e35a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 905 1000 WorkSource{10029}
D/PMS     (  905): releaseWL(43160418): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  905): releaseWL(425f86a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4336e8f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4336e8f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4259ec90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4259ec90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(441ae018): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(441ae018): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4409f538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43063268): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  905): releaseWL(4409f538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360461317
,W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{4308af88: PendingIntentRecord{44286108 com.google.android.gms startService}}) : type=2 triggerAtTime=315360461317 win=-1 tElapsed=315360461317 maxElapsed=551880461315 interval=0 standalone=false
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43682788): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(429e35a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  905): releaseWL(43682788): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(441ce0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(441ce0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43b7c780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=485021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43b7c780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43d6ca10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41ce7490: PendingIntentRecord{424964f0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=491153, Int=0
,D/PMS     (  905): acquireWL(4340d950): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(43d6ca10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42c05a80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4340d950): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(42c05a80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(43ac8c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(43ac8c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
D/PowerUI ( 1115): closing low battery warning: level=100
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42b4c1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{4263ec18: PendingIntentRecord{43959d10 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=527291, Int=300000
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360461317
,D/PMS     (  905): releaseWL(42b4c1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  905): acquireWL(442a0090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(442a0090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4420d8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=545021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4420d8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(437122b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(437122b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4264c4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4264c4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(435afee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=605021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(435afee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43a87b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(43a87b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1245): sku_id=99
D/ContactMessageStore( 1245): start background delete task...
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  905): acquireWL(43523f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=665021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1273): Grow heap (frag case) to 12.642MB for 50416-byte allocation
D/PMS     (  905): releaseWL(43523f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4424af30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4424af30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43844540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43844540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42949f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=725021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42949f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41bb47b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41bb47b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(431790a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/PMS     (  905): releaseWL(431790a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4311d858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=785021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4311d858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43704508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43704508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4382b3f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=845021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4382b3f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43160fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43160fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42c283d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/PMS     (  905): releaseWL(42c283d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42c59038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=905021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42c59038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(442fb2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(442fb2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1),
,I/HtcPowerSaver(  905): << updateStatus,
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e3a868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d2d330: PendingIntentRecord{424301e8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786707, Int=0
D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{4244cef0: PendingIntentRecord{42433b40 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453045646941, Int=900000
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4639): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4639): MY_DEBUG = false
D/PMS     (  905): releaseWL(43e3a868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(44316f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=965021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1273): Grow heap (frag case) to 12.642MB for 50416-byte allocation
D/PMS     (  905): releaseWL(44316f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42cd17f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42cd17f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(426aeac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/SmartSyncUtils( 4639): isEpsOn(), nState = 0
V/AlarmManager(  905): sending alarm PendingIntent{4394dda0: PendingIntentRecord{43847e18 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453045722581, Int=0
,D/PMS     (  905): releaseWL(426aeac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42545150): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4639 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4639): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4639): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4639): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4639): SettingOnTime = 1453096800000, randomSettingOnTime = 1453093531000
D/SmartSyncScreenOnOffTimeReceiver( 4639): SettingOffTime = 1453082400000, randomSettingOffTime = 1453087379000
,D/SmartSyncScreenOnOffTimeReceiver( 4639): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4639): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4639): bNightModeTurnOffOnce = false
,D/PMS     (  905): releaseWL(42545150): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  905): acquireWL(41fa36f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41fa36f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42940788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{4382be90: PendingIntentRecord{42cec428 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1009554, Int=0
,D/PMS     (  905): acquireWL(43083aa8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43083aa8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42940788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425a0478): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2857 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2857/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2857/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024460
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024519
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024525
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024529
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024534
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025756
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025773
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028675
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360461317,
,D/PMS     (  905): releaseWL(425a0478): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms},
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=6 [45][3][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(4422b618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1025021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4422b618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4266bcc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(4266bcc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42126390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42126390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4320c798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1085021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4320c798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426aae60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426aae60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42e3e1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1145021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e3e1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4421fae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/BatteryService(  905): n_update end
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(4421fae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42cf9b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42cf9b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4263a140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1205021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4263a140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44221ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44221ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  905): acquireWL(4260b690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4260b690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(437ce148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b8d300: PendingIntentRecord{41bc63b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1265021, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(437ce148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426bb290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  905): releaseWL(426bb290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4913): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4913): ====startRecUseTime====
D/htc.customization.log.level( 4913):  is 
W/CustomizationLogLevel( 4913): Level value is invalid, use default level 2
D/CustomizationManager( 4913):  Read ACC file spent 0.144 (s)
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4913): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4913): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4913): Parsing tag category name = system
I/CustomizationCIDLoader( 4913): Parsing tag category name = application
I/CustomizationCIDLoader( 4913): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4913): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4913): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4913): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4913): Parsing tag category name = Settings
D/CustomizationManager( 4913):  Read CID file spent 0.205 (s)
D/CustomizationManager( 4913):  All configurations done spent 0.206 (s)
W/HtcNativeFlag( 4913): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4913): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4913): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4913): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4913, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=4476
I/ActivityManager(  905): Killing 4476:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{4235c490 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  905): Copying FileAsset 0x62c4bce8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/InputDispatcher(  905): channel '44232108 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
I/bt-btif ( 1624): BTA_JvDeleteRecord
E/InputDispatcher(  905): channel '44232108 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/bt-btif ( 1624): BTA_JvRfcommStopServer
D/bt-btm  ( 1624): BTM_FreeSCN 
W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '44232108 com.test.thalitest.MainActivity (s)'
D/bt-sdp  ( 1624): SDP_DeleteRecord ok, num_records:16
E/bt-btif ( 1624): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1624): BTM_SEC_CLR[19]: id 58
I/WindowManager(  905): WINDOW DIED Window{44232108 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WindowManager(  905): Failed looking up window
W/WindowManager(  905): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@424442b0 does not exist
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  905): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  905): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  905): WIN DEATH: null
W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4476 uid 10389
W/PackageSettings(  905): Skipping PackageSetting{42175860 com.example.hello/10397} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/PMS     (  905): acquireWL(42b35d50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
D/PMS     (  905): releaseWL(42b35d50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1345): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1345): handle notify Blinkfeed plugin client changed
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/IcingCorporaProvider( 2830): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4929 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  905): acquireWL(4376f100): PARTIAL_WAKE_LOCK  Icing 0x1 2164 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4376f100): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4255f150): PARTIAL_WAKE_LOCK  Icing 0x1 2164 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2830): UpdateCorporaTask done [took 443 ms] updated apps [took 443 ms] 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4929/10100)
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4951 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/GAV2    ( 4929): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4929/10100)
W/ContextImpl( 4951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4969 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
W/GAV2    ( 4929): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  905): Killing 3889:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=3889
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AppTag  ( 4969): getInstance(Context context)
D/AppTag  ( 4969): getInstance(Context context)
D/AppTag  ( 4969): onCreate()
D/PMS     (  905): acquireWL(42c2eca0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4065 10160 null
D/PMS     (  905): releaseWL(42c2eca0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4088): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  905): killProcessQuiet, pid=4551
W/PackageManager(  905): Unable to load service info ResolveInfo{4240eea0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  905): Killing 4551:com.google.android.setupwizard/u0a79 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3889
D/MediaRouterService(  905): Client com.google.android.music (pid 3889): Died!
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PackageBroadcastService( 2164): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2164): Clearing selected account for com.test.thalitest
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ChimeraCfgMgr( 2164): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2164): Module APK com.google.android.play.games already loaded
I/ActivityManager(  905): Recipient 4551
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ChimeraCfgMgr( 2164): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2164): Module APK com.google.android.play.games already loaded
I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2164): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2164): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d2f8598
E/SQLiteLog( 2164): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2164): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca60eb8
W/dalvikvm( 2164): threadid=45: thread exiting with uncaught exception (group=0x4166ce30)
I/LocationSettingsChecker( 2164): Removing dialog suppression flag for package com.test.thalitest
E/DriveAsyncService( 2164): disk I/O error (code 3850)
E/DriveAsyncService( 2164): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2164): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2164): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2164): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2164): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2164): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2164): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2164): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2164): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2164): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2164): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2164): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2164): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2164): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2164): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2164): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2164): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2164): Process: com.google.android.gms, PID: 2164
E/AndroidRuntime( 2164): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2164): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2164): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2164): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2164): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2164): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2164): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2164): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2164): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2164): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2164): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2164): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2164): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2164): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2164): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2164): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2164): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2164): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2164): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
D/Process ( 2164): killProcess, pid=2164
D/Process ( 2164): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  905): Recipient 2164
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.gms (pid 2164) has died.
D/PMS     (  905): handleWLDeath(4255f150): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  905): Client connection lost with reason: 4
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
I/ActivityManager(  905): Resuming delayed broadcast
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20996ms
E/SQLiteLog( 2857): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 2857): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fa7cd8
W/dalvikvm( 2857): threadid=1: thread exiting with uncaught exception (group=0x4166ce30)
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fc38 +
I/Prism.WidgetManager( 1273): onLoadItems() +
E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 2857): FATAL EXCEPTION: main
E/AndroidRuntime( 2857): Process: com.google.process.gapps, PID: 2857
E/AndroidRuntime( 2857): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 2857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2857): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 2857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 2857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 2857): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2857): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2857): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2857): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2857): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 2857): 	... 10 more
D/Process ( 2857): killProcess, pid=2857
D/Process ( 2857): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5000 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 5000): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5000 dbg=false s=true
I/DeviceManagement( 5000): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5000): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5000): WorkflowService: Starting workflow service
I/DeviceManagement( 5000): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41acbf20] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5000): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5000): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5000): PackageUpdateWorkflow: ==================================================
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5014 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5000): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  905): Recipient 2857
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.process.gapps (pid 2857) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20814ms
D/WifiService(  905): Client connection lost with reason: 4
I/DeviceManagement( 5000): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5000): SessionStateController: Checking invariants...
D/Documents( 5014): Loading roots for com.android.providers.downloads.documents
D/Documents( 5014): Loading roots for com.android.externalstorage.documents
I/ActivityManager(  905): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5028 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  905): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5040 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/Process (  905): killProcessQuiet, pid=4580
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4580:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=4594
I/ActivityManager(  905): Killing 4594:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  905): Recipient 4580
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4594
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ExternalStorage( 5028): After updating volumes, found 1 active roots
D/Documents( 5014): Updating roots due to change at content://com.android.externalstorage.documents/root
I/DeviceManagement( 5000): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
D/Documents( 5014): Loading roots for com.android.providers.media.documents
W/dalvikvm( 5040): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 5040): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 5040): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5040): install
I/MultiDex( 5040): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 5040): loading existing secondary dex files
I/MultiDex( 5040): load found 3 secondary dex files
I/MultiDex( 5040): install done
D/Documents( 5014): Loading roots for com.google.android.apps.docs.storage
D/Documents( 5014): Update found 7 roots in 284ms
I/DeviceManagement( 5000): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
D/Documents( 5014): Used cached roots for com.android.providers.downloads.documents
D/Documents( 5014): Loading roots for com.android.externalstorage.documents
I/DeviceManagement( 5000): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41acbf20]
I/DeviceManagement( 5000): WorkflowService: Stopping workflow service
D/Documents( 5014): Used cached roots for com.android.providers.media.documents
D/Documents( 5014): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 5014): Update found 7 roots in 51ms
D/Process (  905): killProcessQuiet, pid=4693
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4693:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
I/ActivityManager(  905): Recipient 4693
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5058 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/GservicesProvider( 5058): Gservices pushing to system: true; secure/global: true
E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b2fc38 -
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
E/SQLiteLog( 1273): (3850) statement aborts at 16: [DELETE FROM appscustomize WHERE _id=68] disk I/O error
E/SQLiteDBG( 1273): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.launcher/databases/launcher.db, handle = 0x5c9ec410
W/dalvikvm( 1273): threadid=13: thread exiting with uncaught exception (group=0x4166ce30)
E/AndroidRuntime( 1273): FATAL EXCEPTION: TaskWorker
E/AndroidRuntime( 1273): Process: com.htc.launcher, PID: 1273
E/AndroidRuntime( 1273): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1273): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1273): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1273): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1273): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1273): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1273): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1273): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1273): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1273): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1273): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1273): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1273): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1273): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.htc.launcher
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
W/dalvikvm( 5058): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
W/dalvikvm( 5058): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/PhoneApp( 1245): -- N1 =0
I/MultiDex( 5058): VM with version 1.6.0 does not have multidex support
D/PhoneApp( 1245): -- N2 =0
I/MultiDex( 5058): install
D/PhoneApp( 1245): -- N3 =0
I/MultiDex( 5058): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 5058): loading existing secondary dex files
I/MultiDex( 5058): load found 3 secondary dex files
I/MultiDex( 5058): install done
W/dalvikvm( 5040): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 5040): VFY: unable to resolve instance field 36
W/dalvikvm( 5040): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 5058): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 5058): VFY: unable to resolve instance field 36
W/dalvikvm( 5058): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
V/JNIHelp ( 5040): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/JNIHelp ( 5058): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ProviderInstaller( 5058): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 5058): COMPAT: Multi user not supported
I/ProviderInstaller( 5040): Installed default security provider GmsCore_OpenSSL
W/ActivityManager(  905):   Force finishing activity com.htc.launcher/.Launcher
W/dalvikvm( 5058): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
I/System  (  905): exec(/system/bin/logcat -v threadtime -t 1024 @ com.android.server.am.HtcErrorReportManager.logProcessResult:845)
W/dalvikvm( 5058): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
D/Process ( 1273): killProcess, pid=1273
D/Process ( 1273): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/BroadcastQueue(  905): Skipping deliver [background] BroadcastRecord{43080a18 u0 android.search.action.SEARCHABLES_CHANGED callingPid=905 callingUid=1000} to ReceiverList{41be12a0 1273 com.htc.launcher/10076/u0 remote:4239b510}: process crashing
D/NativeLibraryUtils( 5040): Installer failed to acquire lock.
D/NativeLibraryUtils( 5040): java.io.IOException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 5040): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
D/NativeLibraryUtils( 5040): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:177)
D/NativeLibraryUtils( 5040): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:587)
D/NativeLibraryUtils( 5040): 	at com.google.android.gms.common.util.ay.b(SourceFile:335)
D/NativeLibraryUtils( 5040): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
D/NativeLibraryUtils( 5040): Caused by: libcore.io.ErrnoException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 5040): 	at libcore.io.Posix.fcntlFlock(Native Method)
D/NativeLibraryUtils( 5040): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:54)
D/NativeLibraryUtils( 5040): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
D/NativeLibraryUtils( 5040): 	... 4 more
W/dalvikvm( 5058): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 5058): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 5058): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 5058): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
W/dalvikvm( 5058): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
W/dalvikvm( 5058): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/dalvikvm( 5058): VFY: unable to resolve instance field 161
W/dalvikvm( 5040): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
D/WifiService(  905): New client listening to asynchronous messages
D/ConnectivityService(  905): getActiveNetworkInfo called by  (5058/10029)
W/dalvikvm( 5058): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/PMS     (  905): acquireWL(42c5bf50): PARTIAL_WAKE_LOCK  Icing 0x1 5040 10029 WorkSource{10029 com.google.android.gms}
D/NativeLibraryUtils( 5058): Install completed successfully. count=14 extracted=0
W/dalvikvm( 5058): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/PMS     (  905): releaseWL(42c5bf50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 5040): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
D/ConnectivityService(  905): getActiveNetworkInfo called by  (5058/10029)
I/ActivityManager(  905): Recipient 1273
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  905): channel '41f22e30 com.htc.launcher.Launcher (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  905): channel '41f22e30 com.htc.launcher.Launcher (s)' ~ Channel is unrecoverably broken and will be disposed!
I/WindowState(  905): WIN DEATH: Window{41f22e30 u0 com.htc.launcher/com.htc.launcher.Launcher}
I/ActivityManager(  905): Process com.htc.launcher (pid 1273) has died.
W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '41f22e30 com.htc.launcher.Launcher (s)'
I/WindowManager(  905): WINDOW DIED Window{41f22e30 u0 com.htc.launcher/com.htc.launcher.Launcher}
I/ActivityManager(  905): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from pid 0
,I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1131940256

```
