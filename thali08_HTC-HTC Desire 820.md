#### Test 539786639813e59_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{44209bc0 u0 com.htc.htclocationservice/.AutoSettingService}
--------- beginning of /dev/log/main
E/cutils-trace( 4429): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4429): ====startRecUseTime====
D/htc.customization.log.level( 4429):  is 
W/CustomizationLogLevel( 4429): Level value is invalid, use default level 2
D/CustomizationManager( 4429):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4429): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4429): Parsing tag category name = system
I/CustomizationCIDLoader( 4429): Parsing tag category name = application
I/CustomizationCIDLoader( 4429): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4429): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4429): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4429): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4429): Parsing tag category name = Settings
D/CustomizationManager( 4429):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4429):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4429): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4429): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4429): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4429): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  900): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  900): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  900): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  900): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  900): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  900): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  900): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4429
D/PMS     (  900): acquireHCC(4251aaa8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 900 1000 null
D/PMS     (  900): acquireHCC(4250df90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 900 1000 null
W/asset   (  900): Copying FileAsset 0x6cc68078 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  900): @test_code: getHtcIntentFlag: 0 obj: 1113057664
D/PMS     (  900): acquireWL(424eb3b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 900 1000 null
I/FeedHostManager( 1264): [onPause]
I/FeedProviderManager( 1264): onPause
I/FeedHostManager( 1264): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d1fe70
I/SocialFeedProvider( 1264): +onPause
I/SocialFeedProvider( 1264): -onPause
I/ActivityManager(  900): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4440 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1264): [trimMemory] 20
W/asset   ( 4440): Copying FileAsset 0x5c7db428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4440): Binding Chromium to main looper Looper (main, tid 1) {41a9b5a8}
I/LibraryLoader( 4440): Expected native library version number "",actual native library version number ""
I/chromium( 4440): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4440): Initializing chromium process, renderers=0
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  900): java.lang.Throwable: stack dump
D/BluetoothManagerService(  900): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423773e0:true
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
D/PMS     (  900): acquireWL(42458098): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  900): acquireWL(423d3eb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  900): releaseWL(42458098): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4440): 1101729760: getState(). Returning 12
I/Adreno-EGL( 4440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4440): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4440): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4440): Local Branch: 
I/Adreno-EGL( 4440): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4440): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4440):                  aa63bbd948f41d15fc72f585e
W/chromium( 4440): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4440): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4440): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4440): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4440): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4440): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4440): CordovaWebView is running on device made by: HTC
,W/AwContents( 4440): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  900): Disable input method client, pid=1264
W/ResourceType( 4440): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4440): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ae2690, mServedView=org.apache.cordova.engine.SystemWebView{41aa82f8 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  900): Displayed com.test.thalitest/.MainActivity: +248ms
I/InputMethodManagerService(  900): Enable input method client, pid=4440
W/AwContents( 4440): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1202): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1202): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1202): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1202): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  900): releaseWL(424eb3b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4440): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4440): JniHelper::setJavaVM(0x41570048), pthread_self() = 1662994600
D/JX-Cordova( 4440): jxcore cordova android initializing
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  900):    returned true
D/WIFI_ICON( 1112): WifiActivity: 0
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/dalvikvm-heap( 4440): Grow heap (frag case) to 11.609MB for 146998-byte allocation
I/dalvikvm-heap( 4440): Grow heap (frag case) to 11.726MB for 220492-byte allocation
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 11.905MB for 330734-byte allocation
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 12.184MB for 496096-byte allocation
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 12.595MB for 744140-byte allocation
,D/PMS     (  900): acquireWL(41f2f0e8): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
D/PMS     (  900): releaseWL(41f2f0e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  900): acquireWL(4236f3a8): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  900): releaseWL(4236f3a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  900): acquireWL(42598350): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  900): releaseWL(42598350): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  900): acquireWL(43178cc8): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  900): releaseWL(43178cc8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 14.070MB for 1674304-byte allocation
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 15.501MB for 2511452-byte allocation
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 17.569MB for 3767174-byte allocation
,W/jxcore-log( 4440): Initializing JXcore engine
,W/jxcore-log( 4440): JXcore engine is ready
,W/jxcore-log( 4440): Starting JXcore engine
,W/CpuWake (  900): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  900): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  900): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  900): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  900): >>release mCpuPerf_Freq wakelock
W/CpuWake (  900): <<release mCpuPerf_Freq wakelock
D/PMS     (  900): releaseHCC(4251aaa8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  900): releaseHCC(4250df90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4440): Platform android
W/jxcore-log( 4440): 
,W/jxcore-log( 4440): Process ARCH arm
W/jxcore-log( 4440): 
,I/jxcore-log( 4440): JXcore Cordova bridge is ready!
I/jxcore-log( 4440): 
,W/jxcore-log( 4440): JXcore engine is started
,I/Choreographer( 4440): Skipped 137 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4440): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4440): Toggling radios to true
I/jxcore-log( 4440): 
,D/BluetoothAdapter( 4440): enable(): BT is already enabled..!
,D/WifiManager( 4440): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  900): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  900): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  900): Settings:Agentvalue: 2
W/Settings:Agent(  900): >> traceCallingStack()
W/Settings:Agent(  900): Process.myPid(): 900
W/Settings:Agent(  900): Process.myTid(): 1295
,W/Settings:Agent(  900): Process.myUid(): 1000
W/Settings:Agent(  900): 
W/Settings:Agent(  900): 
,W/System.err(  900): java.lang.Throwable: stack dump
,W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/WifiService(  900): setWifiEnabled: true pid=4440, uid=10348
E/WifiService(  900): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  900): New client listening to asynchronous messages
I/WifiService(  900): isSprintWifiRestricted(): false
I/WifiService(  900): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  900): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  900): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  900): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  900): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  900): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  900): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  900): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  900): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  900): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  900): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  900): 
W/Settings:Agent(  900): << traceCallingStack(): 5(ms)
D/WifiManager( 4440): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  900): doBoolean: DISCONNECT
D/WifiManager( 4440): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): TDLS: Tear down peers
I/wpa_supplicant( 1129): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4440): Radios toggled
I/jxcore-log( 4440): 
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1129): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1129): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1129): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  900): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1129): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb86ddbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1129):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1129): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1129): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211:, if_removed already cleared - ignore event
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1129): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  900): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
D/HTCRequest(  900): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  900): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  900): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  900):    returned true
D/WifiPerfLock(  900): release()
,D/WifiStateMachine(  900): PerfLock released for exiting ConnectedState
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 0
I/wpa_supplicant( 1129): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
D/ConnectivityService(  900): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  900): acquireWL(433d85b8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 900 1000 null
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  900):    returned true
,D/DhcpStateMachine(  900): [RunningState] Stop DHCP
D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  900): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiNative-wlan0(  900): doBoolean: RECONNECT
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiP2pService(  900): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  900): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): Fast associate: Old scan results
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1129): Scan req (ret=0) - timeout 30 secs
D/WifiNative-wlan0(  900):    returned true
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  900): Enter handleNetworkDisconnect
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  900): stopDataStallAlarm: current tag=19312 mDataStallAlarmIntent=PendingIntent{42d172f8: PendingIntentRecord{4253c498 android broadcastIntent}}
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 0
I/wpa_supplicant( 1129): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  900):    returned true
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/UsbnetStateTracker(  900): isAvailable+-
D/UsbnetStateTracker(  900): reconnect
,D/UsbnetStateTracker(  900): isAvailable+-
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  900): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  900): Provision feature enable=false
D/ConnectivityService(  900): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  900): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  900): default: reconnect()
D/MDST    (  900): default: setTeardownRequested(false)
D/MDST    (  900): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  900): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  900): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  900): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4215): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  900): Exit handleNetworkDisconnect
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiService(  900): New client listening to asynchronous messages
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  900): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  900): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  900): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] entry_id:5   entry:0xb80808e0  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8081000  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8084fd8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8085108  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb80811a8  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb80852e0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8085410  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb8081328  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  900): handleConnectivityChange: resetting
D/ConnectivityService(  900): resetConnections(wlan0, 3)
D/PMS     (  900): acquireWL(422fb020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
D/ConnectivityService(  900): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  900): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  900): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WirelessDisplayService(  900): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  900): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  900): acquireWL(4256c790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
D/ConnectivityService(  900): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  900): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  900): acquireWL(425713f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/ConnectivityService(  900): reportInetCondition for net -1, percentage: 0 by  (1381/10028)
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  900): startScan Pid: 900 Uid 1000
,D/WifiNative-wlan0(  900): doBoolean: SCAN
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  900):    returned false
D/BatSI   (  900): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  900): releaseWL(422fb020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/ConnectivityService(  900): mActiveDefaultNetwork: -1
,D/ConnectivityService(  900): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4215): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  900): releaseWL(4256c790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  900): releaseWL(425713f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  900): releaseWL(423d3eb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  900): acquireWL(43f31f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=103394, Int=0
,D/PMS     (  900): releaseWL(43f31f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1112): now=1450361460059 next=59941
,I/ActivityManager(  900): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4495 uid=10077 gids={50077}
,D/PMS     (  900): acquireWL(43a6b128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10077}
,V/AlarmManager(  900): sending alarm PendingIntent{423548a8: PendingIntentRecord{42165400 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450361460178, Int=60000
,D/PMS     (  900): releaseWL(43a6b128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4495): SMSBackupAgentService started
,D/SMSBackup( 4495): Checking restore status
,D/SMSBackup( 4495): Restore complete
,D/SMSBackup( 4495): cancelCheckAlarm
,D/SMSBackup( 4495): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  900): killProcessQuiet, pid=3453
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3453:com.htc.task/u0a70 (adj 15): empty #17
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Recipient 3453
,V/Tethering(  900): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 3926): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1264): [onReceive] WIFI(1): DISCONNECTED
D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
D/CaptivePortalTracker(  900): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  900): NoActiveNetworkState
,D/Tethering(  900): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  900): bSetPropertyMultiRAB:false
D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/Tethering(  900): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  900): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  900): ipv4Default null
I/Tethering(  900): No IPv4 upstream interface, giving up.
,D/Tethering(  900): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1890/1000)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
I/AlarmManager(  900): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10075)
D/PMS     (  900): acquireWL(42d14af0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.google.android.music (3926/10154)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1505/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.docs (4331/10100)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.docs (4331/10100)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (2445/10021)
,I/ActivityManager(  900): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4509 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,I/SensorManager(  900): mEventCount = 900
,D/GpsLocationProvider(  900): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  900): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  900): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  900): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  900): releaseWL(42d14af0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4509): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4509): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4509): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4509): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4509): Preparing secondary program dexes.
V/DexLibLoader( 4509): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4509): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4509): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4509): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4509): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4509): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4509): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4509): Dex already copied
D/OdexVerifier( 4509): Odex verification is skipped.
,V/DexLibLoader( 4509): Creating class loader
,V/DexLibLoader( 4509): Finished creating class loader
V/DexLibLoader( 4509): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4509): Dex already copied
D/OdexVerifier( 4509): Odex verification is skipped.
,V/DexLibLoader( 4509): Creating class loader,
V/DexLibLoader( 4509): Finished creating class loader
V/DexLibLoader( 4509): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4509): Dex already copied
D/OdexVerifier( 4509): Odex verification is skipped.
,V/DexLibLoader( 4509): Creating class loader
,V/DexLibLoader( 4509): Finished creating class loader
V/DexLibLoader( 4509): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4509): Dex already copied
D/OdexVerifier( 4509): Odex verification is skipped.
,V/DexLibLoader( 4509): Creating class loader,
V/DexLibLoader( 4509): Finished creating class loader
,V/DexLibLoader( 4509): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4509): DexLibLoader.ensureDexLoaded took 19 ms
,W/dalvikvm( 4509): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4509): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4509): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4509): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4509): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4509): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4509): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4509): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4509): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1129): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1129): nl80211: Survey data missing
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1129): Sorted scan results
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1129): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1129): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1129): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1129): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1129): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1129): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1129): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1129): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1129): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1129): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1129): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1129): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1129): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1129): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1129): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1129): wpa_supplicant_pick_network+
I/wpa_supplicant( 1129): Selecting BSS from priority group 1
I/wpa_supplicant( 1129): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1129): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1129): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1129): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1129):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1129):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1129): Start print parameters
I/wpa_supplicant( 1129): wpa_s->wpa_state is 3
I/wpa_supplicant( 1129): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1129): isConcurrentMode() is 0
I/wpa_supplicant( 1129): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1129): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1129): wpa_s->bt_a2dp_status is 0,
I/wpa_supplicant( 1129): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1129): wpa_s->reassociate is 1
I/wpa_supplicant( 1129): wpa_s->is_screen_on 1
I/wpa_supplicant( 1129): wpa_s->ifname wlan0
I/wpa_supplicant( 1129): End print parameters
I/wpa_supplicant( 1129): selected network = 1
D/wpa_supplicant( 1129): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb86df4e8  current_ssid=0x0
D/wpa_supplicant( 1129): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1129): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1129): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1129): check if in concurrent case
I/wpa_supplicant( 1129): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1129): RSN: PMKSA cache search - network_ctx=0xb86df4e8 try_opportunistic=0
D/wpa_supplicant( 1129): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1129): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1129): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1129): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1129): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1129): nl80211: Unsubscribe mgmt frames handle 0xb86de718 (mode change)
D/wpa_supplicant( 1129): nl80211: Subscribe to mgmt frames with non-AP handle 0xb86de718
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1129):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1129):   * freq=2412
D/wpa_supplicant( 1129):   * Auth Type 0
D/wpa_supplicant( 1129):   * WPA Versions 0x2
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1129): nl80211: Connect request send successfully
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_suppli,cant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  900): doString: LIST_DONGLES
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  900): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1129): reply (778) for get BSS: id=0
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1129): freq=5220
I/wpa_supplicant( 1129): level=-48
I/wpa_supplicant( 1129): tsf=0000000105111578
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG7005g
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=1
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): freq=2412
I/wpa_supplicant( 1129): level=-52
I/wpa_supplicant( 1129): tsf=0000000105111596
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG700
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=2
I/wpa_supplicant( 1129): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1129): freq=2437
I/wpa_supplicant( 1129): level=-79
I/wpa_supplicant( 1129): tsf=0000000105111604
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1129): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=3
I/wpa_supplicant( 1129): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): freq=2412
I/wpa_supplicant( 1129): level=-53
I/wpa_supplicant( 1129): tsf=0000000105111591
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1129): ssid=01ABC
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=4
I/wpa_supplicant( 1129): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1129): freq=2427
I/wpa_supplicant( 1129): level=-75
I/wpa_supplicant( 1129): tsf=0000000105111600
I/wpa_supplicant( 1129): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1129): ssid=Gonzos
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=5
I/wpa_supplicant( 1129): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1129): freq=2437
I/wpa_supplicant( 1129): level=-87
I/wpa_supplicant( 1129): tsf=0000000105111608
I/wpa_supplicant( 1129): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=UPC4688432
I/wpa_supplicant( 1129): ####
,D/WirelessDisplayService(  900): getDiscoveryDongleList
D/WifiStateMachine(  900): == begin of scan result ==
,D/WifiStateMachine(  900): == (6) end of scan result ==
,D/WirelessDisplayService(  900): getDiscoveryDongleList
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/WifiStateMachine(  900): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 105111578, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 105111596, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 105111604, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 105111591, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2427, timestamp: 105111600, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 105111608, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): add 6 to mScanResults
D/BatSI   (  900): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  900): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,E/FbInjectorInitializer( 4509): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1129): nl80211: Connect event
D/wpa_supplicant( 1129): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1129): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1129): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1129): Add randomness: count=12 entropy=6
I/wpa_supplicant( 1129): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1129): TDLS: Remove peers on association
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1129): EAPOL: enable timer tick
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1129): htc_wext_set_keepalive +
I/wpa_supplicant( 1129): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1129): getPrivFuncNum +	
I/wpa_supplicant( 1129): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1129): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1129): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1129): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1129): Get randomness: len=32 entropy=7
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/Tethering(  900): interfaceLinkStateChanged wlan0, true
D/Tethering(  900): interfaceStatusChanged wlan0, true
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
,D/WifiMonitor(  900): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  900): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  900): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  900): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  900): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  900): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  900): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  900): Enter handleAssociatedWithEvent
D/WifiStateMachine(  900): Associated
,D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  900): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  900): Exit handleAssociatedWithEvent
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb86de9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1129):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  900): BSSID was changed, update WiFi database
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1129): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f2ab4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1129):    broadcast key
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiApDatabaseHandler(  900): updateConnectedAP...
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1129): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1129): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1129): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1129): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1129): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  900): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): set send_ind_to_ndc = 0
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1129): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1129): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1129): EAPOL authentication completed successfully
I/wpa_supplicant( 1129): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  900): updateConnectedAP...
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  900): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  900): interfaceLinkStateChanged wlan0, true
D/Tethering(  900): interfaceStatusChanged wlan0, true
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  900): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  900): This record is existed, only update it...
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,D/WifiStateMachine(  900): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  900): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  900): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  900): This record is existed, only update it...
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  900): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  900): Provision feature enable=false
D/ConnectivityService(  900): mActiveDefaultNetwork: -1
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4215): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,D/DhcpStateMachine(  900): [StoppedState] Start DHCP
D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 1
I/wpa_supplicant( 1129): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/WifiStateMachine(  900): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  900): acquireWL(43031088): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 900 1000 null
,D/WifiStateMachine(  900): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  900):    returned null
E/WifiStateMachine(  900): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  900):    returned null
D/WifiP2pService(  900): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422e6628 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422e6628 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4509): Verify
,D/BluetoothManagerService(  900): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4440): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4440): 
,I/jxcore-log( 4440): my name is : HTC-HTC Desire 820_PT4385
I/jxcore-log( 4440): 
,I/jxcore-log( 4440): attempting to connect to test coordinator
I/jxcore-log( 4440): 
,I/jxcore-log( 4440): check test folder
I/jxcore-log( 4440): 
,I/jxcore-log( 4440): found test : ./testFindPeers.js
I/jxcore-log( 4440): 
,I/jxcore-log( 4440): found test : ./testReConnect.js
I/jxcore-log( 4440): 
,I/jxcore-log( 4440): found test : ./testSendData.js
I/jxcore-log( 4440): 
,D/WifiService(  900): New client listening to asynchronous messages
,I/jxcore-log( 4440): Test app app.js loaded
I/jxcore-log( 4440): 
,I/Choreographer( 4440): Skipped 161 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4440): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4440): 
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,I/chromium( 4440): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4509): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4509): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 9.508MB for 73240-byte allocation
,D/Process (  900): killProcessQuiet, pid=3271
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  900): Killing 3271:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  900): acquireWL(436fa628): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
I/ActivityManager(  900): Recipient 3271
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  900): acquireWL(43f25c48): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2251 10028 null
,D/PMS     (  900): releaseWL(436fa628): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/PMS     (  900): releaseWL(43f25c48): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1381): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/AutoSetting( 1418): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1418): Util - no network available!
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
,D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1418): service - mHandler: cancel location update
,D/AutoSetting( 1418): service -           changes count: 0
I/ActivityManager(  900): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4538 uid=10078 gids={50078, 3003, 5012}
,W/fb4a(:<default>):UserScope( 4509): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4509): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4509): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4538): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4538): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4538): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4538): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  900): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4552 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  900): killProcessQuiet, pid=4268
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  900): Killing 4268:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
,I/ActivityManager(  900): Recipient 4268
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4509): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache,
D/WifiService(  900): Client connection lost with reason: 4
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  900): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4569 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  900): killProcessQuiet, pid=3887
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  900): Killing 3887:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 3887
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 9.960MB for 84664-byte allocation
E/dalvikvm( 4509): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4509): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4509): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/ContextImpl( 4569): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4509): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4569): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4569): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4569): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4569): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 9.977MB for 28144-byte allocation
E/dalvikvm( 4509): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4509): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4509): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4509): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4509): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4509): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4509): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4509): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4509): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4509): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4509): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4509): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4509): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4509): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 10.019MB for 39954-byte allocation
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 10.095MB for 79892-byte allocation
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4569/10151)
,V/WebViewChromiumFactoryProvider( 4569): Binding Chromium to main looper Looper (main, tid 1) {41aa0118}
,I/LibraryLoader( 4569): Expected native library version number "",actual native library version number ""
,I/chromium( 4569): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4569): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4569): BLUETOOTH permission is missing!
D/PMS     (  900): acquireWL(431a6070): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  900): releaseWL(431a6070): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  900): acquireWL(434ee630): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,I/Adreno-EGL( 4569): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4569): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4569): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4569): Local Branch: 
I/Adreno-EGL( 4569): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4569): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4569):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4569): Starting up...
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4569/10151)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4569/10151)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
,D/Process (  900): killProcessQuiet, pid=4301
,I/ActivityManager(  900): Killing 4301:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  900): Recipient 4301
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,W/BroadcastQueue(  900): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44093120 u0 ReceiverList{4404df30 4509 com.facebook.katana/10026/u0 remote:440416d8}}
,W/BroadcastQueue(  900): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44093120 u0 ReceiverList{4404df30 4509 com.facebook.katana/10026/u0 remote:440416d8}}
,W/BroadcastQueue(  900): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4319ef48 u0 ReceiverList{4319eee8 4509 com.facebook.katana/10026/u0 remote:42c7d178}}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/PMS     (  900): acquireWL(43640810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
,D/PMS     (  900): releaseWL(43640810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1505): Unknown pending intent to remove.
D/PMS     (  900): acquireWL(43199048): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
D/PMS     (  900): releaseWL(43199048): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1129): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1129): EAPOL: disable timer tick
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4509): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4509): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/jxcore-log( 4440): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 4440): 
,D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1129): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2,
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
D/WifiNative-wlan0(  900):    returned true
,D/WifiStateMachine(  900): handlePostDhcpSetup release wake lock during DHCP,
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/WifiP2pService(  900): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  900): releaseWL(43031088): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null,
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1129): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72,
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144,
D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): gateway: /192.168.1.1
D/WifiNative-wlan0(  900): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  900): VerifyingLinkState enter
D/WifiStateMachine(  900): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  900): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  900): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  900): startDataStallAlarm: tag=19314 delay=15s
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  900): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  900): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/WifiWatchdogStateMachine(  900): WAN detection
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  900): Provision feature enable=false
D/ConnectivityService(  900): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  900): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  900): default: teardown()
D/MDST    (  900): default: setTeardownRequested(true)
D/MDST    (  900): default: setEnableApn apnType =default , enable=false
,D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  900): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  900): syncGetConfiguredNetworks
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/MDST    (  900): default: setTeardownRequested(true)
D/ConnectivityService(  900): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  900): Unexpected mtu value: android.net.wifi.WifiStateTracker@423c6d78
D/ConnectivityService(  900): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1112): WifiActivity: 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  900): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  900): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  900): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  900): handleConnectivityChange: resetting
D/Nat464Xlat(  900): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  900): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  900): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  900): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  900): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  900): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  900):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/QuickSettingWifi( 1112): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  900): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  900): acquireWL(431a5578): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/PMS     (  900): acquireWL(425b3390): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
D/PMS     (  900): acquireWL(430a6620): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2251 10028 null
D/PMS     (  900): releaseWL(425b3390): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,I/CheckinService( 2251): Preparing to send checkin request
,I/EventLogService( 2251): Accumulating logs since 1450361411026
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/GoogleHttpClient( 2251): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2251): Using GMS GoogleHttpClient
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  900): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
,D/PMS     (  900): releaseWL(431a5578): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1381): GoogleAccountDataService.getToken()
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1381): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2251): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41ac1540 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 6 2 12
,I/ActivityManager(  900): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4644 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4644): install
,I/MultiDex( 4644): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4644): loading existing secondary dex files
,I/MultiDex( 4644): load found 1 secondary dex files
,I/MultiDex( 4644): install done
,I/ProviderInstaller( 4644): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/Settings( 4644): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  900): releaseWL(433d85b8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  900): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  900): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  900): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  900): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  900): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  900): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  900): NoActiveNetworkState
,V/Tethering(  900): bSetPropertyMultiRAB:false
I/AlarmManager(  900): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(4360cb18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/PMS     (  900): releaseWL(4360cb18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.musicenhancer (3960/10051)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1505/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/Tethering(  900): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1890): Checking Certificates
I/acms    ( 1890): Checking Developer Certificates
,I/acms    ( 1890): Checking Application Certificates
I/acms    ( 1890): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1890): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1890): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1890): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1890): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1890): Updating next query delay: 75600000
I/mlserverapp( 1890): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1890): cancelACMSProgrammedChecks
,I/Tethering(  900): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  900): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/NetworkMonitor( 3926): type=WIFI subType= reason=null isConnected=true
I/Tethering(  900): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  900): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  900): Found interface wlan0
D/Tethering(  900): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078),
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.docs (4331/10100)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1890/1000)
,D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.google.android.music (3926/10154)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10075)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
I/ConnectivityHelper( 1264): [onReceive] WIFI(1): CONNECTED,
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.docs (4331/10100)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(42fb2870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/PMS     (  900): releaseWL(42fb2870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (2445/10021)
,D/PMS     (  900): acquireWL(4241f5f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
,D/PMS     (  900): releaseWL(4241f5f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1381): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,I/jxcore-log( 4440): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4440): 
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1381): [NET] getaddrinfo-,err=8
D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1381): [NET] getaddrinfo-, 1
,D/libc    ( 1381): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e314 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/PMS     (  900): acquireWL(42f089b0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1381 10028 null
,D/AutoSetting( 1418): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4538): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4538): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
D/AutoSetting( 1418): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1418): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1418): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1418): service - handleMessage() setting current location null
D/AutoSetting( 1418): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1418): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (4644/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4569/10151)
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
,D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 176
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1381): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1381): [NET] getaddrinfo-,err=8
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): acquireWL(42594570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
D/PMS     (  900): releaseWL(42594570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1381): Connected
D/PMS     (  900): acquireWL(4248ae18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): releaseWL(42f089b0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  900): handleInetConditionChange: starting a change hold
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): releaseWL(4248ae18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  900): acquireWL(42477010): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1381): Message class mpf
D/ConnectivityService(  900): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  900): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): releaseWL(42477010): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  900): acquireWL(42455918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
D/PMS     (  900): releaseWL(42455918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 2251): Sending checkin request (8884 bytes)
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2251): [NET] getaddrinfo-,err=8
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2251): [NET] getaddrinfo-, 1
,D/libc    ( 2251): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =55f4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 219
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2251): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2251): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=4 [21][1][0]
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  900): BroadcastRSSIForIMS, newrssi =-53 , oldRssi= -200
,D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  900):    returned true
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiStateMachine(  900): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  900): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,W/fb4a(:<default>):UserScope( 4509): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4509): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  900): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  900): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,E/fb4a(:<default>):LocalFbBroadcastManager( 4509): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/PMS     (  900): acquireWL(4242a9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
,D/PMS     (  900): releaseWL(4242a9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [2][0][0]
,W/GLSUser ( 1381): GoogleAccountDataService.getToken()
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1381): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2251): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41ac1bd0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 0 8 2 12
,I/CheckinTask( 2251): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2251): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  900): releaseWL(430a6620): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2251): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ab2d90 that was originally bound here
E/ActivityThread( 2251): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ab2d90 that was originally bound here
E/ActivityThread( 2251): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2251): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2251): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2251): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2251): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2251): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2251): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2251): 	at bks.a(SourceFile:298)
E/ActivityThread( 2251): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2251): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2251): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2251): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1381): GCM config loaded
D/PMS     (  900): releaseWL(434ee630): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  900): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-,err=8
,D/libc    (  900): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4f3d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  900): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  900): Find DNS Address www.htc.com/23.59.123.86
,I/PMS     (  900): Going to sleep due to screen timeout...
,I/ActivityManager(  900): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  900): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42176c38
,W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  900): disable: get sensor name = CM36282 Light sensor
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 2
W/SensorService(  900): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  900): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  900): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42176c38, eanble = 0, strlen(mName) = 59
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  900): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422d9ea8
W/SensorService(  900): Listener[1] = com.htc.smartdim.sensor_eye@41f5e1d0
,W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  900): Couldn't get kernel wake lock stats
V/LightsService(  900): setLight #2: color=#0
D/qdlights(  900): set_light_buttons_func: on=0 brightness=0
V/LightsService(  900): setLight #0: color=#0
,D/WirelessDisplayService(  900): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  900): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  900): mWirelessDisplayManager is null
,W/dalvikvm( 4440): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4440): threadid=1: thread exiting with uncaught exception (group=0x41668e30)
,E/AndroidRuntime( 4440): FATAL EXCEPTION: main
E/AndroidRuntime( 4440): Process: com.test.thalitest, PID: 4440
E/AndroidRuntime( 4440): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4440): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4440): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4440): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4440): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4440): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:153)
E/AndroidRuntime( 4440): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4440): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4440): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4440): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4440): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4440): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4440): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4440): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4440): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4440): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4440): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4440): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4440): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  900): App crashed! Process: com.test.thalitest
W/ActivityManager(  900):   Force finishing activity com.test.thalitest/.MainActivity
,D/SurfaceControl(  900): Excessive delay in blankDisplay() while turning screen off: 375ms
,D/PMS     (  900): nativeSetInteractive:false
D/PMS     (  900): nativeSetInteractive:false done
D/PMS     (  900): nativeSetAutoSuspend:true
,D/PMS     (  900): nativeSetAutoSuspend:true done
,D/PMS     (  900): acquireWL(4386a100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4386a100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(43d32c28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 900 1000 null
,D/HABCtrl (  900): TPE algorithm. remove timeout.
,D/PMS     (  900): OOBE c monitor 11
,I/InputMethodManagerService(  900): screenObserver, isScreenOn=false
D/NfcService( 1248): ScreenObserver: OFF
,D/NfcService( 1248): applyRouting - 0
,D/NfcService( 1248): applyRouting -2
I/InputMethodManagerService(  900): Disable input method client, pid=4440
D/PMS     (  900): acquireWL(43016388): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1248 1027 null
D/PMS     (  900): releaseWL(43016388): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/asset   (  900): Copying FileAsset 0x6bd29aa8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,V/KeyguardServiceDelegate(  900): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425720b0)
,V/KeyguardServiceDelegate(  900): **** SHOWN CALLED ****
,I/IntentController( 1112): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  900): wakingUp
I/InputManager(  900): Cancel all due to getting PMS screen off broadcast
I/WindowManager(  900): No lock screen! windowToken=null
D/PMN     (  900): onScreenOn
,D/AlarmManager(  900): ACTION_SCREEN_ON
I/AlarmManager(  900): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  900): [AlarmQueuing] done recovering
I/AlarmManager(  900): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WifiDataStallTracker(  900): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  900): startDataStallAlarm: tag=19315 delay=15s
I/AlarmManager(  900): [AlarmQueuing] done EPS screen off alarm recovering
,D/WifiNative-wlan0(  900): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): SET_SCREEN_ON:On
I/wpa_supplicant( 1129): htc_wext_set_keepalive +
I/wpa_supplicant( 1129): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1129): getPrivFuncNum +	
I/wpa_supplicant( 1129): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1129): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1129): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
D/WifiNative-wlan0(  900):    returned true
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/MtpService( 2445): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WIFI_ICON( 1112): WifiActivity: 0
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/HtcPowerSaver(  900): updateBatteryInfo
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NfcService( 1248): applyRouting - 0
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/MtpService( 2445): [MTP][onReceive]-
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/AutoSetting( 1418): receiver - intent: android.intent.action.USER_PRESENT
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/NfcService( 1248): applyRouting -2
,D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WirelessDisplayService(  900): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  900): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  900): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PMS     (  900): acquireWL(42564cd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1248 1027 null
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,D/PMS     (  900): releaseWL(42564cd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  900):    returned true
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/ClockThread( 1112): stop update clock
D/WirelessDisplayService(  900): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  900): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  900): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  900): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/TetherSettings( 4215): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4215): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4215): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4215): Cust_ConnectToPC   : spcsc>false
D/        ( 4215): Cust_ConnectToPC   : IPT>true
,D/        ( 4215): Cust_ConnectToPC   : Singel_USB>false
,D/NetworkPolicy(  900): updateScreenOn: false
,W/Settings( 4215): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4215): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4215): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4215): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,I/PSReceiver( 4215): onReceive:android.intent.action.USER_PRESENT
W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
W/ContextImpl( 4215): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4215): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4215): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4215):  defaultType:0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  900): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4691 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1792): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1792): onScreenOn: 1450361467504
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1792): onScreenOn: 1450361467504
D/PMS     (  900): acquireWL(439704e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1505 10028 null
D/PMS     (  900): releaseWL(439704e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/GAV2    ( 4569): Thread[GAThread,5,main]: No campaign data found.
,I/SensorManager(  900): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422d9ea8
,W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  900): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 2
W/SensorService(  900): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  900): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  900): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422d9ea8, eanble = 0, strlen(mName) = 91
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  900): Listener[0] = com.htc.smartdim.sensor_eye@41f5e1d0
,W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  900): goingToSleep
,D/PMS     (  900): acquireWL(43ff55c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 900 1000 null
,D/PMS     (  900): releaseWL(43d32c28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/AlarmManager(  900): ACTION_SCREEN_OFF
I/AlarmManager(  900): [AlarmQueuing] screen off now: 
I/AlarmManager(  900): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  900): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  900): stopDataStallAlarm: current tag=19315 mDataStallAlarmIntent=PendingIntent{43fe4bd8: PendingIntentRecord{4253c498 android broadcastIntent}}
I/AlarmManager(  900): [AlarmQueuing] wifi connection: true
W/ContextImpl( 4691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/WifiNative-wlan0(  900): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): SET_SCREEN_ON:Off
I/wpa_supplicant( 1129): htc_wext_set_keepalive +
I/wpa_supplicant( 1129): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1129): getPrivFuncNum +	
I/wpa_supplicant( 1129): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1129): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1129): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1129): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1129): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  900): acquireWL(43f90a88): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 900 1000 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  900): updateScreenOn: false
,D/PMS     (  900): acquireWL(42b8d188): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4691 1000 null
D/ContactMessageStore( 1233): start background delete task...
D/ContactMessageStore( 1233): size: 0 , 0
D/ContactMessageStore( 1233): Background delete complete
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  900):    returned true
D/SmartSyncUtils( 4691): isEpsOn(), nState = 0
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  900): releaseWL(43f90a88): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/PMS     (  900): releaseWL(42b8d188): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4691): getMobilePolicyEnabled, result = true
,D/Process (  900): killProcessQuiet, pid=4331
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  900): Killing 4331:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/ContextImpl( 4691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4691): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4691): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4691): isEpsOn(), nState = 0
,D/WifiService(  900): New client listening to asynchronous messages
D/AutoSetting( 1418): service - mHandler: cancel location update
,D/AutoSetting( 1418): service -           changes count: 0
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
I/SensorManager(  900): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41f5e1d0
W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  900): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 1
W/SensorService(  900): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  900): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41f5e1d0, eanble = 0, strlen(mName) = 36
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  900): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 0
W/SensorService(  900): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41f5e1d0, eanble = 0, strlen(mName) = 36
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  900): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41f5e1d0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1792): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1792): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1792): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1792): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1792): onScreenOff
D/PMS     (  900): acquireWL(437a7e20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1505 10028 null
D/PMS     (  900): releaseWL(437a7e20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
E/ActivityThread(  900): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422f7cf0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  900): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422f7cf0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  900): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  900): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  900): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  900): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  900): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  900): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  900): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  900): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  900): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  900): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  900): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  900): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  900): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  900): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  900): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  900): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  900): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  900): acquireWL(437604f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
D/PMS     (  900): acquireWL(437af390): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
,D/PMS     (  900): releaseWL(437604f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  900): releaseWL(437af390): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/ActivityManager(  900): Recipient 4331
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  900): Activity pause timeout for ActivityRecord{42335ca0 u0 com.test.thalitest/.MainActivity t2 f}
D/Process (  900): killProcessQuiet, pid=4354
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  900): Killing 4354:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4354
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1233): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1233): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  900): killProcessQuiet, pid=4318
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4318:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4318
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1481): service - handleMessage() stop self
,D/AutoSetting( 1481): service - onDestroy() END
,D/AutoSetting( 1481): service - handleMessage() quit looper
,D/Process (  900): killProcessQuiet, pid=4372
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4372:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4372
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 10.941MB for 24892-byte allocation
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 11.004MB for 48092-byte allocation
,W/ActivityManager(  900): Sleep timeout!  Sleeping now.
,D/PMS     (  900): releaseWL(43ff55c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 11.011MB for 48752-byte allocation
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 11.035MB for 42334-byte allocation
,D/libc    ( 4509): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4509): [NET] getaddrinfo-,err=8
D/libc    ( 4509): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4509): [NET] getaddrinfo-, 1
,D/libc    ( 4509): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ef7e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 38
D/libc    (  363): [NET]res_nsend:resplen=93
D/libc    (  363): [NET]res_queryN: exit 3, ancount=3
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4509): [NET] getaddrinfo_proxy-, success
,I/global  ( 4509): call createSocket() return a new socket.
D/libc    ( 4509): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
,D/libc    ( 4509): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4509): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4509): [NET] getaddrinfo-,err=8
,D/PMS     (  900): acquireWL(44030850): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4509 10026 null
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 11.088MB for 36962-byte allocation
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 11.118MB for 55438-byte allocation
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 11.174MB for 66130-byte allocation
,I/dalvikvm-heap( 4509): Grow heap (frag case) to 11.207MB for 57340-byte allocation
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  900): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,I/global  ( 4509): I/O error closing connection
I/global  ( 4509): java.net.SocketException: Socket is closed
I/global  ( 4509): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4509): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4509): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4509): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4509): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4509): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4509): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4509): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4509): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4509): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4509): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4509): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4509): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4509): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4509): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4509): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4509): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4509): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4509): Removing a connection that never existed!,
D/PMS     (  900): releaseWL(44030850): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,W/ActivityManager(  900): Activity destroy timeout for ActivityRecord{42335ca0 u0 com.test.thalitest/.MainActivity t2 f}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  900): acquireWL(440084e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  900): releaseWL(440084e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1418): service - mHandler: update timezone
,D/AutoSetting( 1481): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1481): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  900): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  900): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1481): service - onCreate()
,D/AutoSetting( 1481): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1481): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1481): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1481): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1481): service - mHandler: update timezone
,D/AutoSetting( 1481): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1481): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1481): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1481): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41ac7118 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  900): acquireWL(436135a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{4217d5c0: PendingIntentRecord{4240b710 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140802, Int=0
,V/AlarmManager(  900): sending alarm PendingIntent{437af448: PendingIntentRecord{425ebba8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141159, Int=0
,D/GpsLocationProvider(  900): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  900): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  900): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  900): acquireWL(4360dff8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/PMS     (  900): acquireWL(43609298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
,D/AutoSetting( 1418): service - handleMessage() stop self
D/libc    (  900): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-,err=8
D/libc    (  900): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
D/PMS     (  900): releaseWL(436135a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  900): releaseWL(43609298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4f63 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =,
D/libc    (  363): [NET] NOT IN CACHE
,D/AutoSetting( 1418): service - onDestroy() END
,D/AutoSetting( 1418): service - handleMessage() quit looper
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  900): [NET] getaddrinfo_proxy-, success
I/global  (  900): call createSocket() return a new socket.
D/libc    (  900): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  900): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  900): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  900): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  900):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  900): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  900): killProcessQuiet, pid=3960
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3960:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 3960
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  900): releaseWL(4360dff8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{4374f6e8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  900): acquireWL(4318f760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=163394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4318f760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1481): service - handleMessage() stop self
,D/AutoSetting( 1481): service - onDestroy() END
,D/AutoSetting( 1481): service - handleMessage() quit looper
,D/Process (  900): killProcessQuiet, pid=4389
,I/ActivityManager(  900): Killing 4389:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  900): Recipient 4389
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  900): acquireWL(42c9ab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PMS     (  900): releaseWL(42c9ab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1233): switchBindHtcMsgCursor: null
,D/PMS     (  900): acquireWL(41eb2e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(41eb2e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(42297d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=223394, Int=0
,D/PMS     (  900): releaseWL(42297d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(41f2f0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{41ecff58: PendingIntentRecord{42b7b588 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226099, Int=0
,I/ActivityManager(  900): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4732 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  900): sending alarm PendingIntent{4246c170: PendingIntentRecord{42469e20 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450361576858, Int=10800000
,D/PMS     (  900): releaseWL(41f2f0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.aurora (4732/10047)
,D/Process (  900): killProcessQuiet, pid=4403
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4403:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4403
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/PMS     (  900): acquireWL(423b0c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): releaseWL(423b0c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42478390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{42eb4fc8: PendingIntentRecord{42b7b588 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231026, Int=0
,D/PMS     (  900): releaseWL(42478390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  900): acquireWL(424d3980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): releaseWL(424d3980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  900): acquireWL(436187e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=283394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(436187e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(422d6c18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(422d6c18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
,I/HtcPowerSaver(  900): >> updateStatus
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(425c9050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(425c9050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(425ab3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=343394, Int=0
I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(425ab3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  900): acquireWL(422b1658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(422b1658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1381): GoogleAccountDataService.getToken()
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1381): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/GLSActivity( 1381): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1381): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1381): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1381): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1381): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1381): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1381): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1381): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41af6750 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4158): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4158): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4158): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4158): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4158): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4158): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4158): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4158): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1112): com.google.android.gms 2 10 3 12
,D/libc    ( 4158): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4158): [NET] getaddrinfo-,err=8
D/libc    ( 4158): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4158): [NET] getaddrinfo-, 1
,D/libc    ( 4158): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2363 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4158): [NET] getaddrinfo_proxy-, success
,I/global  ( 4158): call createSocket() return a new socket.
D/libc    ( 4158): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4158): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4158): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4158): [NET] getaddrinfo-,err=8
,D/PMS     (  900): acquireWL(44025ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(44025ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  900): updateBatteryInfo
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  900): acquireWL(425bb218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=403394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(425bb218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process ( 4440): killProcess, pid=4440
,D/Process ( 4440): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/PMS     (  900): acquireWL(4253fdd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{43ed5e80: PendingIntentRecord{425c70c0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=410758, Int=300000
,I/InputMethodManagerService(  900): Disable input method client, pid=4440
,D/PMS     (  900): releaseWL(4253fdd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,I/ActivityManager(  900): Recipient 4440
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Process com.test.thalitest (pid 4440) has died.
I/WindowState(  900): WIN DEATH: Window{422efea0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  900): Client connection lost with reason: 4
,D/PMS     (  900): acquireWL(440d0728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): releaseWL(440d0728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
,I/HtcPowerSaver(  900): >> updateStatus
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(431a9560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): releaseWL(431a9560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42a153c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=463394, Int=0
I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42a153c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  900): acquireWL(425b80b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(425b80b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1129): nl80211: Disconnect event
I/wpa_supplicant( 1129): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1129): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  900): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  900): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  900): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  900): Enter handleNetworkDisconnect
I/wpa_supplicant( 1129): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1129): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb86ddbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1129):    addr=c0:ff:d4:d3:aa:48
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
E/wpa_supplicant( 1129): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1129): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state INITIALIZE
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG70,0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 0
I/wpa_supplicant( 1129): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  900):    returned true
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  900):    returned true
D/WifiP2pService(  900): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  900): [RunningState] Stop DHCP
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): Wireless event: cmd=0x8b15 len=20
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
,D/Tethering(  900): interfaceStatusChanged wlan0, false
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
,D/Tethering(  900): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  900): Exit handleNetworkDisconnect
D/WifiPerfLock(  900): release()
,D/WifiStateMachine(  900): PerfLock released for exiting ConnectedState
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  900): stopDataStallAlarm: current tag=19316 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 0
I/wpa_supplicant( 1129): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  900): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  900): acquireWL(4341de08): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 900 1000 null
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  900): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  900): Provision feature enable=false
D/ConnectivityService(  900): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  900): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  900):    returned true
D/libc    (  900): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/UsbnetStateTracker(  900): isAvailable+-
D/UsbnetStateTracker(  900): reconnect
,D/UsbnetStateTracker(  900): isAvailable+-
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  900): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  900): default: reconnect()
D/MDST    (  900): default: setTeardownRequested(false)
D/MDST    (  900): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  900): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  900): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  900): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WISPrService( 4215): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  900): doBoolean: SET pno 1
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='1'
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '52 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 52 Failed to remove route from default table (No such process)'
D/ConnectivityService(  900): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  900): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1129): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1129): nl80211: Event message available
,D/wpa_supplicant( 1129): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  900):    returned true
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  900): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] entry_id:4   entry:0xb8084e88  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8085410  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb80851e8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8085108  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8084fd8  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8080f38  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/ConnectivityService(  900): handleConnectivityChange: resetting
D/ConnectivityService(  900): resetConnections(wlan0, 3)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/PMS     (  900): acquireWL(434c40e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
D/ConnectivityService(  900): flush DNS cache for net 1(wlan0)
D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4215): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/PMS     (  900): acquireWL(43fcadd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Nat464Xlat(  900): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  900): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  900): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): releaseWL(43fcadd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  900): acquireWL(44088700): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WirelessDisplayService(  900): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1129): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WirelessDisplayService(  900): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/ConnectivityService(  900): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
D/ConnectivityService(  900): reportInetCondition for net -1, percentage: 0 by  (1381/10028)
D/PMS     (  900): releaseWL(434c40e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/WifiStateMachine(  900): startScan Pid: 900 Uid 1000
,D/WifiNative-wlan0(  900): doBoolean: SET pno 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1129): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
D/WifiNative-wlan0(  900):    returned true
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WifiNative-wlan0(  900): doBoolean: SCAN
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/BatSI   (  900): WIFI scan started for: 450a0300 uid:1000
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1129): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1129): Failed to initiate AP scan
I/wpa_supplicant( 1129): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  900):    returned true
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  900): releaseWL(44088700): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  900): mActiveDefaultNetwork: -1
,D/ConnectivityService(  900): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  900): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  900): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/GpsLocationProvider(  900): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  900): acquireWL(431db7d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/GpsLocationProvider(  900): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  900): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  900): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
D/Tethering(  900): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  900): bSetPropertyMultiRAB:false
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
D/CaptivePortalTracker(  900): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1129): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1129): Failed to initiate AP scan
I/wpa_supplicant( 1129): Failed to initiate AP scan, Failed_to_scan_counter:2
D/CaptivePortalTracker(  900): NoActiveNetworkState
,D/Tethering(  900): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  900): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  900): ipv4Default null
I/Tethering(  900): No IPv4 upstream interface, giving up.
,D/Tethering(  900): TetherMasterSM: InitialState processMessage what=3
,D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/PMS     (  900): releaseWL(431db7d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1505/10028)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10075)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.google.android.music (3926/10154)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1890/1000)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/ConnectivityHelper( 1264): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 3926): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (2445/10021)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/PMS     (  900): acquireWL(424dd3a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
,D/PMS     (  900): acquireWL(4321be08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2251 10028 null
,D/PMS     (  900): releaseWL(424dd3a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1381): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/PMS     (  900): releaseWL(4321be08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/AutoSetting( 1418): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4538): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4538): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1418): Util - no network available!
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
,D/AutoSetting( 1418): service - onCreate()
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4569/10151)
,D/AutoSetting( 1418): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  900): request 422bcba0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  900): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1418): service - mHandler: cancel location update
,D/AutoSetting( 1418): service -           changes count: 0
,I/dalvikvm-heap( 4193): Grow heap (frag case) to 13.524MB for 1821008-byte allocation
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4193): Grow heap (frag case) to 15.212MB for 1821008-byte allocation
,I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1129): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1129): Failed to initiate AP scan
,I/wpa_supplicant( 1129): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1129): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1129): nl80211: Survey data missing
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1129): Sorted scan results
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1129): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1129): Add randomness: count=13 entropy=0
D/wpa_supplicant( 1129): Add randomness: count=14 entropy=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1129): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1129): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1129): wpa_supplicant_pick_network+
I/wpa_supplicant( 1129): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1129): Selecting BSS from priority group 1
I/wpa_supplicant( 1129): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1129): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1129): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1129):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1129): No APs found - clear blacklist and try again
E/wpa_supplicant( 1129): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1129): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1129): Selecting BSS from priority group 1
I/wpa_supplicant( 1129): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1129): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1129): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1129): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1129):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1129):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1129): Start print parameters
I/wpa_supplicant( 1129): wpa_s->wpa_state is 3
I/wpa_supplicant( 1129): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1129): isConcurrentMode() is 0
I/wpa_supplicant( 1129): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1129): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1129): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1129): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1129): wpa_s->reassociate is 0
I/wpa_supplicant( 1129): wpa_s->is_screen_on 0
I/wpa_supplicant( 1129): wpa_s->ifname wlan0
I/wpa_supplicant( 1129): End print parameters
I/wpa_supplicant( 1129): selected network = 7
D/wpa_supplicant( 1129): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb86df4e8  current_ssid=0x0
D/wpa_supplicant( 1129): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1129): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1129): TDLS: TDLS is allo,wed in the target BSS
I/wpa_supplicant( 1129): check if in concurrent case
I/wpa_supplicant( 1129): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  900): doBoolean: SET pno 1
D/WifiMonitor(  900): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1129): RSN: PMKSA cache search - network_ctx=0xb86df4e8 try_opportunistic=0
D/wpa_supplicant( 1129): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1129): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1129): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1129): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1129): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1129): nl80211: Unsubscribe mgmt frames handle 0xb86de718 (mode change)
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1129): nl80211: Subscribe to mgmt frames with non-AP handle 0xb86de718
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1129):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1129):   * freq=2412
D/wpa_supplicant( 1129):   * Auth Type 0
,D/wpa_supplicant( 1129):   * WPA Versions 0x2,
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1129): nl80211: Connect request send successfully
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1129): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  900):    returned false
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  900): doString: LIST_DONGLES
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  900): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1129): reply (238) for get BSS: id=6
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1129): freq=5220
I/wpa_supplicant( 1129): level=-48
I/wpa_supplicant( 1129): tsf=0000000482081819
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG7005g
I/wpa_supplicant( 1129): ====
,I/wpa_supplicant( 1129): id=7
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): freq=2412
I/wpa_supplicant( 1129): level=-55
I/wpa_supplicant( 1129): tsf=0000000482081845
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG700
I/wpa_supplicant( 1129): ####
D/WirelessDisplayService(  900): getDiscoveryDongleList
D/WifiStateMachine(  900): == begin of scan result ==
,D/WifiStateMachine(  900): == (2) end of scan result ==
,D/WirelessDisplayService(  900): getDiscoveryDongleList
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  900): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 482081819, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 482081845, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): add 2 to mScanResults
D/BatSI   (  900): WIFI scan stopped for: 440a0300 uid:1000
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/WifiNotificationController(  900): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/wpa_supplicant( 1129): nl80211: Event message available
,D/wpa_supplicant( 1129): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1129): nl80211: Connect event
I/wpa_supplicant( 1129): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1129): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1129): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/HTCRequest(  900): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  900): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  900): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
,D/HTCRequest(  900): WifiMonitor:getFreqFromEventString() 0
D/HTCRequest(  900): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING - ret = 0
D/HTCRequest(  900): WifiMonitor:getStatusCodeFromEventString() 1
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=0
,D/HTCRequest(  900): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  900): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1129): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiStateMachine(  900): Enter handleAssociateRejectEvent
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
,D/WifiStateMachine(  900): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18,
,D/WifiStateMachine(  900): Exit handleAssociateRejectEvent
,I/wpa_supplicant( 1129): wpa_supplicant_scan enter
,I/wpa_supplicant( 1129): State: DISCONNECTED -> SCANNING,
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1129): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiStateMachine(  900): startScan Pid: 900 Uid 1000
,D/WifiNative-wlan0(  900): doBoolean: SET pno 0
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 1129): wpa_supplicant_scan enter
,D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: SCAN
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  900):    returned false
D/BatSI   (  900): WIFI scan started for: 450a0300 uid:1000
,D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1129): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1129): nl80211: Survey data missing
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1129): Sorted scan results
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1129): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1129): Add randomness: count=15 entropy=2
D/wpa_supplicant( 1129): Add randomness: count=16 entropy=3
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1129): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1129): wpa_supplicant_pick_network+
I/wpa_supplicant( 1129): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1129): Selecting BSS from priority group 1
I/wpa_supplicant( 1129): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1129): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1129): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1129):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1129): No APs found - clear blacklist and try again
E/wpa_supplicant( 1129): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1129): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1129): Selecting BSS from priority group 1
I/wpa_supplicant( 1129): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1129): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1129): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1129): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1129):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1129):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1129): Start print parameters
I/wpa_supplicant( 1129): wpa_s->wpa_state is 3
I/wpa_supplicant( 1129): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1129): isConcurrentMode() is 0
I/wpa_supplicant( 1129): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1129): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1129): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1129): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1129): wpa_s->reassociate is 0
I/wpa_supplicant( 1129): wpa_s->is_screen_on 0
I/wpa_supplicant( 1129): wpa_s->ifname wlan0
I/wpa_supplicant( 1129): End print parameters
I/wpa_supplicant( 1129): selected network = 7
D/wpa_supplicant( 1129): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb86df4e8  current_ssid=0x0
D/wpa_supplicant( 1129): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1129): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1129): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1129): check if in concurrent case
,I/wpa_supplicant( 1129): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1129): RSN: PMKSA cache search - network_ctx=0xb86df4e8 try_opportunistic=0
D/wpa_supplicant( 1129): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1129): RSN: No PMKSA cache entry found,
I/wpa_supplicant( 1129): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1129): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 1129): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1129): nl80211: Unsubscribe mgmt frames handle 0xb86de718 (mode change)
D/wpa_supplicant( 1129): nl80211: Subscribe to mgmt frames with non-AP handle 0xb86de718
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1129):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1129):   * freq=2412
D/wpa_supplicant( 1129):   * Auth Type 0
,D/wpa_supplicant( 1129):   * WPA Versions 0x2
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1129): nl80211: Connect request send successfully
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/WifiMonitor(  900): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  900): doBoolean: SET pno 1
,D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1129): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  900):    returned false
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  900): doString: LIST_DONGLES
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  900): doString: BSS RANGE=0- MASK=0x21987
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  900): getDiscoveryDongleList
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1129): reply (238) for get BSS: id=6
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1129): freq=5220
I/wpa_supplicant( 1129): level=-48
I/wpa_supplicant( 1129): tsf=0000000486272353
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG7005g
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=7
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): freq=2412
I/wpa_supplicant( 1129): level=-55,
I/wpa_supplicant( 1129): tsf=0000000486272380
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG700
I/wpa_supplicant( 1129): ####
D/WifiStateMachine(  900): == begin of scan result ==
,D/WifiStateMachine(  900): == (2) end of scan result ==
,D/WirelessDisplayService(  900): getDiscoveryDongleList
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/WifiStateMachine(  900): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 486272353, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 486272380, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): add 2 to mScanResults
D/BatSI   (  900): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  900): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1129): nl80211: Connect event
,D/wpa_supplicant( 1129): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1129): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1129): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1129): Add randomness: count=17 entropy=4
I/wpa_supplicant( 1129): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1129): TDLS: Remove peers on association
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  900): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1129): EAPOL: enable timer tick
,D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1129): htc_wext_set_keepalive +
I/wpa_supplicant( 1129): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1129): getPrivFuncNum +	
I/wpa_supplicant( 1129): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1129): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1129): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1129): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  900): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  900): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1129): Get randomness: len=32 entropy=5
D/HTCRequest(  900): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  900): interfaceLinkStateChanged wlan0, true
D/Tethering(  900): interfaceStatusChanged wlan0, true
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/HTCRequest(  900): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  900): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  900): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  900): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  900): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  900): Enter handleAssociatedWithEvent
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  900): Associated
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  900): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  900): Exit handleAssociatedWithEvent
,D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  900): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  900): updateConnectedAP...
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,D/WifiStateMachine(  900): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/wpa_supplicant( 1129): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb86de9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1129):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=1
D/WifiApDatabaseHandler(  900): isDuplicate in c0:ff:d4:d3:aa:48-0: true
I/wpa_supplicant( 1129): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,D/WifiStateMachine(  900): This record is existed, only update it...
D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f2ab4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1129):    broadcast key
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1129): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1129): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1129): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1129): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1129): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  900): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1129): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1129): set send_ind_to_ndc = 0
,I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING (1)+
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING - ret = 0
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=1
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1129): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Authorized
D/Tethering(  900): interfaceLinkStateChanged wlan0, true
D/Tethering(  900): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1129): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1129): EAPOL authentication completed successfully
I/wpa_supplicant( 1129): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...,
,D/WifiStateMachine(  900): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  900): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  900): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  900): This record is existed, only update it...
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  900): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  900): Provision feature enable=false
D/ConnectivityService(  900): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = false<<<<<
,D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/WISPrService( 4215): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  900): updateConnectedAP...
,D/WifiNative-wlan0(  900): doBoolean: SET pno 0
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  900):    returned true
,D/DhcpStateMachine(  900): [StoppedState] Start DHCP
,D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiStateMachine(  900): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  900): acquireWL(434e9d40): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 900 1000 null
,D/WifiStateMachine(  900): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 1
I/wpa_supplicant( 1129): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  900):    returned null
E/WifiStateMachine(  900): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1129): nl80211: Event message available
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/wpa_supplicant( 1129): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1129): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiNative-wlan0(  900):    returned null
D/WifiP2pService(  900): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422e6628 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  900): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422e6628 target=com.android.internal.util.StateMachine$SmHandler }
I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1129): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1129): EAPOL: disable timer tick
,D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  900): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1129): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  900):    returned true
,D/WifiStateMachine(  900): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  900): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  900): releaseWL(434e9d40): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=33 [3][1][0]
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  900):    returned true
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  900): gateway: /192.168.1.1
D/WifiNative-wlan0(  900): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1129): htc_wext_set_keepalive +
I/wpa_supplicant( 1129): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1129): getPrivFuncNum +	
I/wpa_supplicant( 1129): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1129): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1129): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1129): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1129): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  900): VerifyingLinkState enter
D/WifiStateMachine(  900): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  900): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  900): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  900): WAN detection
V/NetworkPolicy(  900): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  900): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  900): Provision feature enable=false
D/ConnectivityService(  900): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  900): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  900): default: teardown()
D/MDST    (  900): default: setTeardownRequested(true)
,D/MDST    (  900): default: setEnableApn apnType =default , enable=false
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  900): default: setTeardownRequested(true)
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  900): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WISPrService( 4215): >>>>>WISPrService start isConnected = true<<<<<
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  900): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
E/ConnectivityService(  900): Unexpected mtu value: android.net.wifi.WifiStateTracker@423c6d78
D/ConnectivityService(  900): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/WifiStateMachine(  900): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  900): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  900): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  900): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  900): handleConnectivityChange: resetting
D/Nat464Xlat(  900): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  900): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  900): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  900): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  900): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  900): acquireWL(4404bfe0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  900): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  900):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
,I/QuickSettingWifi( 1112): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  900): acquireWL(42fd3ed0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  900): acquireWL(425bc880): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2251 10028 null
D/PMS     (  900): releaseWL(42fd3ed0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,I/CheckinService( 2251): Preparing to send checkin request
,I/EventLogService( 2251): Accumulating logs since 1450361463229
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2251): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2251): Using GMS GoogleHttpClient
,D/ConnectivityService(  900): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
,D/PMS     (  900): releaseWL(4404bfe0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1381): GoogleAccountDataService.getToken()
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1381): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2251): awaiting user notification for token
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41ac7ef8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 9 3 12
,W/Settings( 4644): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (4644/10028)
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  900): releaseWL(4341de08): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  900): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  900): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  900): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/CaptivePortalTracker(  900): NoActiveNetworkState
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1264): [onReceive] WIFI(1): CONNECTED
I/acms    ( 1890): Checking Certificates
I/acms    ( 1890): Checking Developer Certificates
I/acms    ( 1890): Checking Application Certificates
I/acms    ( 1890): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1890): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
I/acms    ( 1890): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
I/acms    ( 1890): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
I/acms    ( 1890): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1890): Updating next query delay: 75600000
I/mlserverapp( 1890): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1890): cancelACMSProgrammedChecks
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1890/1000)
D/PMS     (  900): acquireWL(43470690): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10075)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1505/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
,D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.google.android.music (3926/10154)
I/NetworkMonitor( 3926): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
V/Tethering(  900): bSetPropertyMultiRAB:false
D/Tethering(  900): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
I/Tethering(  900): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  900): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  900): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  900): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  900): Found interface wlan0
,D/Tethering(  900): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/PMS     (  900): acquireWL(42b6c790): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/GpsLocationProvider(  900): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  900): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  900): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  900): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  900): releaseWL(42b6c790): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  900): releaseWL(43470690): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (2445/10021)
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,I/CheckinTask( 2251): Sending checkin request (8962 bytes)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2251): [NET] getaddrinfo-,err=8
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2251): [NET] getaddrinfo-, 1
D/libc    ( 2251): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8e1b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  900): acquireWL(4408e0a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
,D/PMS     (  900): releaseWL(4408e0a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1381): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): acquireWL(43396038): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1381 10028 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 180
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1381): [NET] getaddrinfo-,err=8
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1381): [NET] getaddrinfo-, 1
D/libc    ( 1381): [NET] getaddrinfo_proxy+
D/libc    ( 2251): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f7ae +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/AutoSetting( 1418): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4538): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/MobileConnectivityChangeReceiver( 4538): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1418): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
,D/AutoSetting( 1418): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1418): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4569/10151)
,I/dalvikvm-heap( 4193): Grow heap (frag case) to 16.957MB for 1821008-byte allocation
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
D/libc    ( 1381): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=50 [6][3][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2251): [NET] getaddrinfo-,err=8
,D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1381): [NET] getaddrinfo-,err=8
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): acquireWL(43483958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
D/PMS     (  900): releaseWL(43483958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1381): Connected
D/PMS     (  900): acquireWL(43f31108): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): releaseWL(43396038): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  900): handleInetConditionChange: starting a change hold
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): releaseWL(43f31108): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  900): acquireWL(434f9f50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
,D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1381): Message class mpf
D/ConnectivityService(  900): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  900): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/PMS     (  900): acquireWL(43752dd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
,D/PMS     (  900): releaseWL(434f9f50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  900): releaseWL(43752dd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WifiStateMachine(  900): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  900): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  900): acquireWL(43f3a168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
,D/PMS     (  900): releaseWL(43f3a168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=14 [21][3][0]
,W/GLSUser ( 1381): GoogleAccountDataService.getToken()
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1381): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2251): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41e04ba8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 2 10 2 12
,I/CheckinTask( 2251): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2251): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  900): releaseWL(425bc880): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2251): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41af5d28 that was originally bound here
E/ActivityThread( 2251): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41af5d28 that was originally bound here
E/ActivityThread( 2251): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2251): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2251): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2251): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2251): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2251): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2251): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2251): 	at bks.a(SourceFile:298)
E/ActivityThread( 2251): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2251): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2251): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2251): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1381): GCM config loaded
D/ConnectivityService(  900): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  900): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,D/libc    (  900): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-,err=8
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =176a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  900): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  900): Find DNS Address www.htc.com/23.59.123.86
,D/PMS     (  900): acquireWL(44064300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(44064300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{428e63e0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
,D/ConnectivityService(  900): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  900): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1418): service - mHandler: update timezone
,D/AutoSetting( 1418): service - handleMessage() stop self
,D/AutoSetting( 1418): service - handleMessage() quit looper
,D/AutoSetting( 1481): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1418): service - onDestroy() END
W/ActivityManager(  900): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1481): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1481): service - onCreate()
W/ActivityManager(  900): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1481): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1481): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1481): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1481): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1481): service - mHandler: update timezone
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1481): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1481): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1481): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1481): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41ac7118 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 1 7 2 11
,D/PMS     (  900): acquireWL(43741128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=523394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43741128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43713878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43713878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{44031680 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/AutoSetting( 1481): service - handleMessage() stop self
,D/AutoSetting( 1481): service - onDestroy() END
,D/AutoSetting( 1481): service - handleMessage() quit looper
,D/PMS     (  900): acquireWL(435133e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(435133e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1129): nl80211: Disconnect event
I/wpa_supplicant( 1129): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1129): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  900): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  900): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  900): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  900): Enter handleNetworkDisconnect
I/wpa_supplicant( 1129): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1129): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1129): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb86ddbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1129):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1129): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplic,ant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 0
I/wpa_supplicant( 1129): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  900): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/Tethering(  900): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): Wireless event: cmd=0x8b15 len=20
,D/WifiNative-wlan0(  900):    returned true
D/WifiP2pService(  900): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  900): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
,D/Tethering(  900): interfaceStatusChanged wlan0, false
D/DhcpStateMachine(  900): [RunningState] Stop DHCP
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  900): Exit handleNetworkDisconnect
D/WifiPerfLock(  900): release()
D/WifiStateMachine(  900): PerfLock released for exiting ConnectedState
D/libc    (  900): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  900): stopDataStallAlarm: current tag=19317 mDataStallAlarmIntent=null
D/ConnectivityService(  900): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 0
I/wpa_supplicant( 1129): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
,D/UsbnetStateTracker(  900): isAvailable+-
D/UsbnetStateTracker(  900): reconnect
D/UsbnetStateTracker(  900): isAvailable+-
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/ConnectivityService(  900): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  900): Provision feature enable=false
D/PMS     (  900): acquireWL(42f087e8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 900 1000 null
D/ConnectivityService(  900): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  900): default: reconnect()
D/MDST    (  900): default: setTeardownRequested(false)
D/MDST    (  900): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/WifiP2pService(  900): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  900):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = false<<<<<
D/WifiP2pService(  900): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  900): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  900): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  900): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 4215): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  900): doBoolean: SET pno 1
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS,
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '73 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 73 Failed to remove route from default table (No such process)'
D/ConnectivityService(  900): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  900): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '75 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 75 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  900): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1129): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1129): nl80211: Event message available
,D/wpa_supplicant( 1129): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '76 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 76 Failed to remove route from default table (No such process)'
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] entry_id:2   entry:0xb80850f8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8085428  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8084fd8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4215): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  900): handleConnectivityChange: resetting
D/ConnectivityService(  900): resetConnections(wlan0, 3)
D/PMS     (  900): acquireWL(4253fc40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/PMS     (  900): acquireWL(42399aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
D/ConnectivityService(  900): flush DNS cache for net 1(wlan0)
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
D/Nat464Xlat(  900): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  900): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  900): releaseWL(42399aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  900): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  900): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WirelessDisplayService(  900): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  900): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1129): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/PMS     (  900): acquireWL(41a92c40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
D/ConnectivityService(  900): reportInetCondition for net -1, percentage: 0 by  (1381/10028)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  900): startScan Pid: 900 Uid 1000
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  900): doBoolean: SET pno 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1129): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
D/wpa_supplicant( 1129): nl80211: Event message available
,D/wpa_supplicant( 1129): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: SCAN
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1129): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1129): Failed to initiate AP scan
,I/wpa_supplicant( 1129): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  900):    returned true
D/PMS     (  900): releaseWL(4253fc40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/BatSI   (  900): WIFI scan started for: 450a0300 uid:1000
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/ConnectivityService(  900): mActiveDefaultNetwork: -1
,D/ConnectivityService(  900): handleInetConditionChange: no active default network - ignore
,D/PMS     (  900): releaseWL(41a92c40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/NativeDaemonConnector.ResponseQueue(  900): more buffered than allowed: 10 >= 10
,E/NativeDaemonConnector.ResponseQueue(  900): Removing request: null (5)
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  900): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  900): [AlarmQueuing] connectivity wifi: false
,I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1129): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1129): Failed to initiate AP scan
,I/wpa_supplicant( 1129): Failed to initiate AP scan, Failed_to_scan_counter:2
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
D/GpsLocationProvider(  900): [handleMessage] UPDATE_NETWORK_STATE
D/Tethering(  900): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  900): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  900): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/Tethering(  900): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  900): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  900): ipv4Default null
I/Tethering(  900): No IPv4 upstream interface, giving up.
D/Tethering(  900): TetherMasterSM: InitialState processMessage what=3
D/GpsLocationProvider(  900): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  900): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  900): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  900): NoActiveNetworkState
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(42499068): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): releaseWL(42499068): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1505/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,I/NetworkMonitor( 3926): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1264): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10075)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.google.android.music (3926/10154)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1890/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (2445/10021)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
,D/PMS     (  900): acquireWL(43727878): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
,D/PMS     (  900): acquireWL(42e39a60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2251 10028 null
,D/PMS     (  900): releaseWL(43727878): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/GCM     ( 1381): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/PMS     (  900): releaseWL(42e39a60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/AutoSetting( 1418): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4538): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1418): Util - no network available!
,D/MobileConnectivityChangeReceiver( 4538): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
D/AutoSetting( 1418): service - onCreate()
,D/AutoSetting( 1418): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4569/10151)
,D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  900): request 422bcba0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  900): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1418): service - mHandler: cancel location update
,D/AutoSetting( 1418): service -           changes count: 0
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
,D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1129): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1129): Failed to initiate AP scan
,I/wpa_supplicant( 1129): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1129): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1129): nl80211: Survey data missing
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1129): Sorted scan results
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1129): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1129): Add randomness: count=18 entropy=0
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1129): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1129): wpa_supplicant_pick_network+
I/wpa_supplicant( 1129): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1129): Selecting BSS from priority group 1
I/wpa_supplicant( 1129): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1129): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1129): No APs found - clear blacklist and try again
E/wpa_supplicant( 1129): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1129): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1129): Selecting BSS from priority group 1
I/wpa_supplicant( 1129): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1129): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1129): clear disabled list - type=1
I/wpa_supplicant( 1129): No suitable network found
W/wpa_supplicant( 1129): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1129): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  900): doBoolean: SET pno 1
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Received scan results (1 BSSes)
D/WifiMonitor(  900): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/wpa_supplicant( 1129): nl80211: Survey data missing
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1129): Sorted scan results
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1129): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1129): Add randomness: count=19 entropy=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1129): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1129): wpa_supplicant_pick_network+
I/wpa_supplicant( 1129): clear disabled list - type=1
I/wpa_supplicant( 1129): No suitable network found
W/wpa_supplicant( 1129): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1129): State: DISCONNECTED -> INACTIVE
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  900): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1129): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  900): doString: LIST_DONGLES
,D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =INACTIVE
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  900): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1129): reply (238) for get BSS: id=6
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1129): freq=5220
I/wpa_supplicant( 1129): level=-48
I/wpa_supplicant( 1129): tsf=0000000568901872
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG7005g
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=7
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): freq=2412
I/wpa_supplicant( 1129): level=-55
I/wpa_supplicant( 1129): tsf=0000000486272380
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG700
I/wpa_supplicant( 1129): ####
,D/WirelessDisplayService(  900): getDiscoveryDongleList
D/WifiP2pService(  900): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@42fe0b70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@42fe0b70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@42fe0b70 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/WifiStateMachine(  900): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 568901872, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 486272380, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): add 2 to mScanResults
,D/WifiStateMachine(  900): == begin of scan result ==
,D/WifiStateMachine(  900): == (2) end of scan result ==
,D/WirelessDisplayService(  900): getDiscoveryDongleList
D/BatSI   (  900): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  900): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/WifiStateMachine(  900): startScan Pid: 900 Uid 1000
,D/WifiNative-wlan0(  900): doBoolean: SET pno 0
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1129): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1129): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1129): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: SCAN
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1129): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1129): Failed to initiate AP scan
,I/wpa_supplicant( 1129): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  900):    returned true
D/BatSI   (  900): WIFI scan started for: 450a0300 uid:1000
,I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1129): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1129): Failed to initiate AP scan
,I/wpa_supplicant( 1129): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1129): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1129): Failed to initiate AP scan
,I/wpa_supplicant( 1129): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1129): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1129): nl80211: Survey data missing
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1129): Sorted scan results
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1129): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
D/wpa_supplicant( 1129): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1129): Add randomness: count=20 entropy=2
D/wpa_supplicant( 1129): Add randomness: count=21 entropy=3
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1129): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1129): WPS: AP[1] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1129): wpa_supplicant_pick_network+
I/wpa_supplicant( 1129): Selecting BSS from priority group 1
I/wpa_supplicant( 1129): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1129): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1129): 1: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1129): clear disabled list - type=1
I/wpa_supplicant( 1129): No suitable network found
W/wpa_supplicant( 1129): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1129): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1129): nl80211: Survey data missing
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1129): Sorted scan results
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1129): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
D/wpa_supplicant( 1129): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1129): Add randomness: count=22 entropy=4
D/wpa_supplicant( 1129): Add randomness: count=23 entropy=5
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1129): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1129): WPS: AP[1] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1129): wpa_supplicant_pick_network+
I/wpa_supplicant( 1129): clear disabled list - type=1
I/wpa_supplicant( 1129): No suitable network found
W/wpa_supplicant( 1129): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1129): State: INACTIVE -> INACTIVE
,D/WifiNative-wlan0(  900): doBoolean: SET pno 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  900): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1129): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1129): nl80211: Event message available
,D/wpa_supplicant( 1129): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  900): doString: LIST_DONGLES
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  900): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1129): reply (262) for get BSS: id=6
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1129): freq=5220
I/wpa_supplicant( 1129): level=-48
I/wpa_supplicant( 1129): tsf=0000000574714599
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG7005g
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=8
I/wpa_supplicant( 1129): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1129): freq=2437
I/wpa_supplicant( 1129): level=-79
I/wpa_supplicant( 1129): tsf=0000000574714625
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1129): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1129): ####
,D/WirelessDisplayService(  900): getDiscoveryDongleList
D/WifiStateMachine(  900): == begin of scan result ==
,D/WifiStateMachine(  900): == (2) end of scan result ==
D/WifiStateMachine(  900): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 574714599, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/WifiStateMachine(  900): 1: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 574714625, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): add 2 to mScanResults
D/BatSI   (  900): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  900): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  900): getDiscoveryDongleList
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1129): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1129): nl80211: Survey data missing
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1129): Sorted scan results
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
D/wpa_supplicant( 1129): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1129): Add randomness: count=24 entropy=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1129): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1129): WPS: AP[1] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1129): WPS: AP[2] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1129): wpa_supplicant_pick_network+
I/wpa_supplicant( 1129): Selecting BSS from priority group 1,
I/wpa_supplicant( 1129): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1129): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1129): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1129):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1129):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1129): Start print parameters
I/wpa_supplicant( 1129): wpa_s->wpa_state is 3
I/wpa_supplicant( 1129): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1129): isConcurrentMode() is 0
I/wpa_supplicant( 1129): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1129): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1129): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1129): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1129): wpa_s->reassociate is 0
I/wpa_supplicant( 1129): wpa_s->is_screen_on 0
I/wpa_supplicant( 1129): wpa_s->ifname wlan0
I/wpa_supplicant( 1129): End print parameters
I/wpa_supplicant( 1129): selected network = 9
D/wpa_supplicant( 1129): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb86df4e8  current_ssid=0x0
D/wpa_supplicant( 1129): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1129): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1129): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1129): check if in concurrent case
I/wpa_supplicant( 1129): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  900): doString: LIST_DONGLES
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1129): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1129): RSN: PMKSA cache search - network_ctx=0xb86df4e8 try_opportunistic=0
D/wpa_supplicant( 1129): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1129): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1129): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1129): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1129): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1129): nl80211: Unsubscribe mgmt frames handle 0xb86de718 (mode change)
D/wpa_supplicant( 1129): nl80211: Subscribe to mgmt frames with non-AP handle 0xb86de718
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/w,pa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Register frame type=0xd0 nl_handle=0xb86de718
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1129): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1129):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1129):   * freq=2412
D/wpa_supplicant( 1129):   * Auth Type 0
D/wpa_supplicant( 1129):   * WPA Versions 0x2
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1129): nl80211: Connect request send successfully
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  900): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1129): reply (380) for get BSS: id=6
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1129): freq=5220
I/wpa_supplicant( 1129): level=-48
I/wpa_supplicant( 1129): tsf=0000000574714599
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG7005g
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=8
I/wpa_supplicant( 1129): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1129): freq=2437
I/wpa_supplicant( 1129): level=-79
I/wpa_supplicant( 1129): tsf=0000000574714625
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1129): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=9
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): freq=2412
I/wpa_supplicant( 1129): level=-52
I/wpa_supplicant( 1129): tsf=0000000576707320
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG700
I/wpa_supplicant( 1129): ####
,D/WirelessDisplayService(  900): getDiscoveryDongleList
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/WifiStateMachine(  900): == begin of scan result ==
D/WifiStateMachine(  900): == (3) end of scan result ==
,D/WirelessDisplayService(  900): getDiscoveryDongleList
D/WifiStateMachine(  900): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 574714599, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  900): 1: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 574714625, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 576707320, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): add 3 to mScanResults
D/WifiNotificationController(  900): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1129): nl80211: Connect event
D/wpa_supplicant( 1129): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1129): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1129): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1129): Add randomness: count=25 entropy=7
I/wpa_supplicant( 1129): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1129): TDLS: Remove peers on association
D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1129): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1129): EAPOL: enable timer tick
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1129): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1129): Get randomness: len=32 entropy=8
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1129): htc_wext_set_keepalive +
I/wpa_supplicant( 1129): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1129): getPrivFuncNum +	
I/wpa_supplicant( 1129): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1129): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1129): htc_wext_set_keepalive - ret = 0
D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  900): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  900): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  900): WifiMonitor:getFreqFromEventString() 2412,
D/HTCRequest(  900): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  900): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  900): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  900): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  900): interfaceLinkStateChanged wlan0, true
D/Tethering(  900): interfaceStatusChanged wlan0, true
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700,
D/Tethering(  900): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1129): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb86de9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1129):    addr=c0:ff:d4:d3:aa:48
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  900): Enter handleAssociatedWithEvent
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 10
,D/WifiStateMachine(  900): Associated
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1129): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f2ab4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1129):    broadcast key
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1129): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1129): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1129): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1129): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1129): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1129): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1129): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1129): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  900): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): set send_ind_to_ndc = 0
,I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1129): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1129): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1129): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1129): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1129): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1129): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1129): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1129): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1129): EAPOL authentication completed successfully
I/wpa_supplicant( 1129): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1129): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1129): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1129): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  900): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  900): Exit handleAssociatedWithEvent
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  900): BSSID was changed, update WiFi database
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  900): updateConnectedAP...
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  900): interfaceLinkStateChanged wlan0, true
D/Tethering(  900): interfaceStatusChanged wlan0, true
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  900): updateConnectedAP...
D/WifiStateMachine(  900): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  900): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  900): This record is existed, only update it...
D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...,
,D/WifiStateMachine(  900): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  900): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  900): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  900): This record is existed, only update it...
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  900): updateConnectedAP...
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  900): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  900): Provision feature enable=false
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  900): mActiveDefaultNetwork: -1
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = false<<<<<
,D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/WISPrService( 4215): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiNative-wlan0(  900): doBoolean: SET pno 0
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1129): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  900):    returned true
,D/DhcpStateMachine(  900): [StoppedState] Start DHCP
,D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: DRIVER SETSUSPENDMODE 0
,D/WifiStateMachine(  900): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  900): acquireWL(43f37060): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 900 1000 null
,D/WifiStateMachine(  900): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 1
I/wpa_supplicant( 1129): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  900):    returned true
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1129): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  900):    returned null
E/WifiStateMachine(  900): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  900):    returned null,
D/WifiP2pService(  900): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422e6628 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422e6628 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1129): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1129): EAPOL: disable timer tick
,D/WifiStateMachine(  900): startScan Pid: 900 Uid 1000
,D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  900): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1129): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1129): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  900): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  900): releaseWL(43f37060): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  900):    returned true
,D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  900): gateway: /192.168.1.1
D/WifiNative-wlan0(  900): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1129): htc_wext_set_keepalive +
I/wpa_supplicant( 1129): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1129): getPrivFuncNum +	
I/wpa_supplicant( 1129): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1129): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1129): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1129): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1129): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  900): VerifyingLinkState enter
D/WifiStateMachine(  900): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
,D/WifiNative-wlan0(  900): doBoolean: SCAN TYPE=ONLY
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/BatSI   (  900): WIFI scan started for: 450a0300 uid:1000
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1129): wpa_supplicant_scan enter
I/wpa_supplicant( 1129): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1129): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1129): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  900): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
V/NetworkPolicy(  900): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiWatchdogStateMachine(  900): WAN detection
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  900): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  900): Provision feature enable=false
D/ConnectivityService(  900): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  900): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  900): default: teardown()
D/MDST    (  900): default: setTeardownRequested(true)
D/MDST    (  900): default: setEnableApn apnType =default , enable=false
,D/MDST    (  900): default: setTeardownRequested(true)
,D/ConnectivityService(  900): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,E/ConnectivityService(  900): Unexpected mtu value: android.net.wifi.WifiStateTracker@423c6d78
,D/ConnectivityService(  900): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WISPrService( 4215): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  900): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,I/QuickSettingWifi( 1112): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  900): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
E/NetdConnector(  900): NDC Command {84 interface route add wlan0 default 192.168.1.0 24 0.0.0.0} took too long (798ms)
,D/ConnectivityService(  900): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiStateMachine(  900): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  900): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  900): handleConnectivityChange: resetting
D/Nat464Xlat(  900): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  900): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  900): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  900): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  900): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  900): acquireWL(440234b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/ConnectivityService(  900): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WirelessDisplayService(  900): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  900):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
,D/PMS     (  900): acquireWL(43ff3ba8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1129): Change stage from stage0 to stage3
D/PMS     (  900): releaseWL(440234b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  900): acquireWL(43474270): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2251 10028 null
D/PMS     (  900): releaseWL(43ff3ba8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,I/CheckinService( 2251): Preparing to send checkin request
,I/EventLogService( 2251): Accumulating logs since 1450361845074
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2251): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2251): Using GMS GoogleHttpClient
,D/ConnectivityService(  900): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1381): GoogleAccountDataService.getToken()
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1381): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2251): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41b01e50 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/PMS     (  900): releaseWL(42f087e8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  900): NetTransition Wakelock for ConnectedState released by timeout
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 11 3 12
,W/Settings( 4644): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (4644/10028)
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4644): Local Branch: 
I/Adreno-EGL( 4644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4644):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  900): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  900): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
,D/GpsLocationProvider(  900): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  900): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  900): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  900): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
D/PMS     (  900): acquireWL(439326e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/PMS     (  900): releaseWL(439326e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/CaptivePortalTracker(  900): NoActiveNetworkState
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
I/acms    ( 1890): Checking Certificates
I/acms    ( 1890): Checking Developer Certificates
,I/acms    ( 1890): Checking Application Certificates
I/acms    ( 1890): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1890): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1890): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1890): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1890): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1890): Updating next query delay: 75600000
I/CheckinTask( 2251): Sending checkin request (8961 bytes)
I/mlserverapp( 1890): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1890): cancelACMSProgrammedChecks
I/ConnectivityHelper( 1264): [onReceive] WIFI(1): CONNECTED
I/NetworkMonitor( 3926): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1890/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1505/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4538/10078)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10075)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.google.android.music (3926/10154)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2251): [NET] getaddrinfo-,err=8
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2251): [NET] getaddrinfo-, 1
D/libc    ( 2251): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
V/Tethering(  900): bSetPropertyMultiRAB:false
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =144 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
D/libc    (  363): [NET] NOT IN CACHE
D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  900): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
I/Tethering(  900): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  900): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  900): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  900): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  900): Found interface wlan0
D/Tethering(  900): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(43f425d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
D/PMS     (  900): releaseWL(43f425d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (2445/10021)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4509/10026)
D/PMS     (  900): acquireWL(43fe5ec0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
D/PMS     (  900): releaseWL(43fe5ec0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1381): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1381): [NET] getaddrinfo-,err=8
D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1381): [NET] getaddrinfo-, 1
,D/libc    ( 1381): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c188 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  900): acquireWL(42ff3a10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1381 10028 null
,D/AutoSetting( 1418): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4538): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
D/MobileConnectivityChangeReceiver( 4538): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1418): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1418): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1418): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4569/10151)
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (4193/10160)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,D/wpa_supplicant( 1129): nl80211: Event message available
D/wpa_supplicant( 1129): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1129): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1129): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1129): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1129): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1129): nl80211: Survey data missing
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1129): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1129): Sorted scan results
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1129): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1129): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1129): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-74
D/wpa_supplicant( 1129): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1129): Add randomness: count=26 entropy=0
D/wpa_supplicant( 1129): Add randomness: count=27 entropy=1
D/wpa_supplicant( 1129): Add randomness: count=28 entropy=2
D/wpa_supplicant( 1129): Add randomness: count=29 entropy=3
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  900): doString: LIST_DONGLES
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  900): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1129): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1129): reply (491) for get BSS: id=6
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1129): freq=5220
I/wpa_supplicant( 1129): level=-48
I/wpa_supplicant( 1129): tsf=0000000581623010
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG7005g
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=9
I/wpa_supplicant( 1129): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): freq=2412
I/wpa_supplicant( 1129): level=-55
I/wpa_supplicant( 1129): tsf=0000000581623053
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1129): ssid=NG700
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=10
I/wpa_supplicant( 1129): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1129): freq=2412
I/wpa_supplicant( 1129): level=-52
I/wpa_supplicant( 1129): tsf=0000000581623038
I/wpa_supplicant( 1129): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1129): ssid=01ABC
I/wpa_supplicant( 1129): ====
I/wpa_supplicant( 1129): id=11
I/wpa_supplicant( 1129): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1129): freq=2427
I/wpa_supplicant( 1129): level=-74
I/wpa_supplicant( 1129): tsf=0000000581623065
I/wpa_supplicant( 1129): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1129): ssid=Gonzos
I/wpa_supplicant( 1129): ####
,D/WifiStateMachine(  900): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WirelessDisplayService(  900): getDiscoveryDongleList
D/WifiStateMachine(  900): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 581623010, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 581623053, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 581623038, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2427, timestamp: 581623065, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): add 4 to mScanResults
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,V/ScoreHelper(  900): Only print Top 10 in ApScanList
,V/ScoreHelper(  900):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  900):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  900):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  900):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  900):  + computeScore(NG700): 1
,D/WifiStateMachine(  900): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  900): == begin of scan result ==
,D/WifiStateMachine(  900): == (4) end of scan result ==
,D/WirelessDisplayService(  900): getDiscoveryDongleList
D/BatSI   (  900): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  900): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/libc    (  900): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-,err=8
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =fd9b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/WifiStateMachine(  900): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  900): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{4257d600 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 238
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2251): [NET] getaddrinfo_proxy-, success
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1381): [NET] getaddrinfo_proxy-, success
,D/libc    (  900): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  900): Find DNS Address www.htc.com/23.59.123.86
,D/PMS     (  900): acquireWL(438de7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=583394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(438de7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    ( 1381): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1381): [NET] getaddrinfo-,err=8
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): acquireWL(43bc8480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
D/PMS     (  900): releaseWL(43bc8480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2251): [NET] getaddrinfo-,err=8
,D/GCM     ( 1381): Connected,
D/PMS     (  900): acquireWL(4253e318): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): releaseWL(42ff3a10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  900): handleInetConditionChange: starting a change hold
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/PMS     (  900): releaseWL(4253e318): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  900): acquireWL(42e810e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
,D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1381): Message class mpf
D/ConnectivityService(  900): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  900): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/PMS     (  900): acquireWL(44025ba0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
,D/PMS     (  900): releaseWL(44025ba0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  900): releaseWL(42e810e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/ConnectivityService(  900): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  900): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=28 [38][11][0]
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1129): Change stage from stage3 to stage0
,D/PMS     (  900): acquireWL(434c7fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
,D/PMS     (  900): releaseWL(434c7fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=0 [3][0][0]
,W/GLSUser ( 1381): GoogleAccountDataService.getToken()
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1381): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1381): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 2251): awaiting user notification for token
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41b1f5a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 2 9 2 12
,I/CheckinTask( 2251): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2251): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
D/PMS     (  900): releaseWL(43474270): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2251): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41a957a0 that was originally bound here
E/ActivityThread( 2251): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41a957a0 that was originally bound here
E/ActivityThread( 2251): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2251): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2251): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2251): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2251): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2251): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2251): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2251): 	at bks.a(SourceFile:298)
E/ActivityThread( 2251): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2251): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2251): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2251): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1381): GCM config loaded
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  900): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  900): acquireWL(4346c1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): releaseWL(4346c1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1418): service - has update message, not stop
,D/AutoSetting( 1418): service - mHandler: update timezone
,D/AutoSetting( 1481): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1481): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  900): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1481): service - onCreate()
W/ActivityManager(  900): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1481): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1481): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1481): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1481): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1481): service - mHandler: update timezone
,D/AutoSetting( 1481): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1481): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1481): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1481): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41beb720 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  900): acquireWL(439a43c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(439a43c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
,D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1233): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1233): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1233): sku_id=99
D/ContactMessageStore( 1233): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1233): start background delete task...
D/ContactMessageStore( 1233): size: 0 , 0
,D/ContactMessageStore( 1233): Background delete complete
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{435c6db0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1418): service - handleMessage() stop self
,D/AutoSetting( 1418): service - onDestroy() END
,D/AutoSetting( 1418): service - handleMessage() quit looper
,D/AutoSetting( 1481): service - handleMessage() stop self
,D/AutoSetting( 1481): service - onDestroy() END
,D/AutoSetting( 1481): service - handleMessage() quit looper
,D/PMS     (  900): acquireWL(425a6e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=643393, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(425a6e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43a51748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43a51748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(4386f018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=703394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4386f018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42bb5c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42bb5c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  900): updateBatteryInfo
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42a96818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): releaseWL(42a96818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
,I/HtcPowerSaver(  900): >> updateStatus
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43bb0e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=763394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43bb0e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(44033260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/PMS     (  900): releaseWL(44033260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(44048578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{43ed5e80: PendingIntentRecord{425c70c0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=710758, Int=300000
,V/AlarmManager(  900): sending alarm PendingIntent{41d49ad8: PendingIntentRecord{423d1530 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784987, Int=0
,D/ConnectivityService(  900): Sampling interval elapsed, updating statistics ..
,D/PMS     (  900): releaseWL(44048578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  900): Done.
,D/ConnectivityService(  900): Setting timer for 720seconds
,D/PMS     (  900): acquireWL(4402fa70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4402fa70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4350ea90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=823394, Int=0
,D/PMS     (  900): releaseWL(4350ea90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(436100d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(436100d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(43fd5410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): releaseWL(43fd5410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  900): updateBatteryInfo
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4324e3c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=883394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4324e3c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43f2e7a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PMS     (  900): releaseWL(43f2e7a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4403d690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4403d690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43ffd640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=943394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43ffd640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42b8d2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42b8d2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
,I/HtcPowerSaver(  900): >> updateStatus
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42c8a388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42c8a388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(437b9c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1003394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(437b9c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43ffca20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{42332018: PendingIntentRecord{41bd8ac0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450362297355, Int=900000
,V/AlarmManager(  900): sending alarm PendingIntent{42c632a0: PendingIntentRecord{42c8d118 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450362367738, Int=0
,W/ContextImpl( 4691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4691): call getInstance()
,D/SmartSyncUtils( 4691): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4691): MY_DEBUG = false
D/PMS     (  900): acquireWL(42e833e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4691 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4691): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4691): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4691): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4691): SettingOnTime = 1450400400000, randomSettingOnTime = 1450397721000
,D/SmartSyncScreenOnOffTimeReceiver( 4691): SettingOffTime = 1450396800000, randomSettingOffTime = 1450397421000
,D/SmartSyncScreenOnOffTimeReceiver( 4691): bDayMode = false
,D/PMS     (  900): releaseWL(43ffca20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4691): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4691): bNightModeTurnOffOnce = false
D/PMS     (  900): releaseWL(42e833e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,D/PMS     (  900): acquireWL(4361b8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PMS     (  900): releaseWL(4361b8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42d1f7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42d1f7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43f34fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1063394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43f34fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42440f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  900): releaseWL(42440f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(435e3020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/PMS     (  900): releaseWL(435e3020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43902558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1123394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43902558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(41f425f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(41f425f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43086ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43086ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4324cbf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1183394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4324cbf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(4374a108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): BroadcastReceiver::onReceive+
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): releaseWL(4374a108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4402ec40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
D/PMS     (  900): releaseWL(4402ec40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  900): updateBatteryInfo
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  900): acquireWL(431537f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1243394, Int=0
I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(431537f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43931cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): releaseWL(43931cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4402bd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4402bd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1112): closing low battery warning: level=100
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43075068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1303394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43075068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(4404d3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): releaseWL(4404d3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(44022458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): releaseWL(44022458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  900): updateBatteryInfo
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43f15260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1363394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43f15260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43b16a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): releaseWL(43b16a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/PowerUI ( 1112): closing low battery warning: level=100
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42581b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): releaseWL(42581b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42579c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1423394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42579c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(437bb180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1112): closing low battery warning: level=100
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PMS     (  900): releaseWL(437bb180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(432fb740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/PMS     (  900): releaseWL(432fb740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42ff1068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1483394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42ff1068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(433d0dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  900): updateBatteryInfo
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): releaseWL(433d0dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4401b8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4401b8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
,D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(44023070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1543394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(44023070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42e8c8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  900): releaseWL(42e8c8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43c38540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  900): releaseWL(43c38540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42c9e068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1603394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42c9e068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42b7b990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): releaseWL(42b7b990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43607fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
I/BatteryService(  900): n_update end
D/PMS     (  900): releaseWL(43607fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
,I/HtcPowerSaver(  900): >> updateStatus
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43254300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1663394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43254300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(438c57d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(438c57d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42fdbd78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1723394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42fdbd78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43ffe700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  900): releaseWL(43ffe700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4312d300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
D/PMS     (  900): releaseWL(4312d300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(436ba7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1783394, Int=0
I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(436ba7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,D/PMS     (  900): acquireWL(437861e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10028}
,V/AlarmManager(  900): sending alarm PendingIntent{43fc6bd8: PendingIntentRecord{4254cb88 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1483636, Int=0
,D/PMS     (  900): acquireWL(43f8bb58): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1381 10028 null
,V/AlarmManager(  900): sending alarm PendingIntent{41d49ad8: PendingIntentRecord{423d1530 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505024, Int=0
,V/AlarmManager(  900): sending alarm PendingIntent{41ccdd50: PendingIntentRecord{42432c80 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1807396, Int=0
V/AlarmManager(  900): sending alarm PendingIntent{430e3c68: PendingIntentRecord{42572b60 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450362424892, Int=1800000
,D/PMS     (  900): releaseWL(43f8bb58): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/ConnectivityService(  900): Sampling interval elapsed, updating statistics ..
,D/PMS     (  900): acquireWL(43f44a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
,D/PMS     (  900): acquireWL(43b7c908): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 900 1000 null
,D/PMS     (  900): releaseWL(43f44a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/PMS     (  900): acquireWL(425aab70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
,D/PMS     (  900): acquireWL(437b90f0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2251 10028 null
,D/ConnectivityService(  900): Done.
,D/ConnectivityService(  900): Setting timer for 720seconds
,D/PMS     (  900): releaseWL(43b7c908): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  900): releaseWL(425aab70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  900): releaseWL(437861e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  900): acquireWL(434cb0c8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2251 10028 null
,D/PMS     (  900): releaseWL(437b90f0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 2251): Aggregate from 1450361936880 (log), 1450360624833 (data)
,D/PMS     (  900): releaseWL(434cb0c8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  900): acquireWL(4323f4f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1381 10028 null
,D/GCM     ( 1381): Message class mow
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1381/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  900): handleInetConditionChange: starting a change hold
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1381/10028)
,D/PMS     (  900): releaseWL(4323f4f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  900): acquireWL(43ed2930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1381 10028 null
,D/PMS     (  900): releaseWL(43ed2930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  900): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  900): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1129): environment dirty rate=1 [104][2][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1129): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1129): nl80211: survey data missing!
E/wpa_supplicant( 1129): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1129): environment dirty rate=0 [0][0][0]
,D/PMS     (  900): acquireWL(4301a998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
D/PMS     (  900): releaseWL(4301a998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  900): acquireWL(43308c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422f9318: PendingIntentRecord{424b0070 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820409, Int=1800000
D/PMS     (  900): acquireWL(433dc6b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
,V/AlarmManager(  900): sending alarm PendingIntent{42332018: PendingIntentRecord{41bd8ac0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450363197355, Int=900000
,D/PMS     (  900): releaseWL(433dc6b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ProcessStatsService(  900): Prepared write state in 44ms
,I/ProcessStatsService(  900): Prepared write state in 23ms
,D/PMS     (  900): releaseWL(43308c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,I/ProcessStatsService(  900): Pruning old procstats: /data/system/procstats/state-2015-12-16-20-30-48.bin
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,D/PMS     (  900): acquireWL(428073f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1843394, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(428073f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(4360a678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4360a678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43744790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43744790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4389e780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{422c8ba8: PendingIntentRecord{4203b138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1903394, Int=0
D/Process (  900): killProcessQuiet, pid=4158
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  900): killProcessQuiet, pid=4069
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  900): Killing 4158:com.android.vending/u0a73 (adj 15): empty for 1816s
I/ActivityManager(  900): Killing 4069:com.google.android.gm/u0a107 (adj 15): empty for 1829s
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4389e780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  900): Recipient 4069
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Recipient 4158
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4964): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4964): ====startRecUseTime====
D/htc.customization.log.level( 4964):  is 
W/CustomizationLogLevel( 4964): Level value is invalid, use default level 2
D/CustomizationManager( 4964):  Read ACC file spent 0.068 (s)
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4964): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4964): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4964): Parsing tag category name = system
I/CustomizationCIDLoader( 4964): Parsing tag category name = application
I/CustomizationCIDLoader( 4964): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4964): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4964): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4964): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4964): Parsing tag category name = Settings
D/CustomizationManager( 4964):  Read CID file spent 0.110 (s)
D/CustomizationManager( 4964):  All configurations done spent 0.111 (s)
W/HtcNativeFlag( 4964): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4964): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4964): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4964): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  900): deletePackageAsUser: pkg=com.test.thalitest, pid=4964, uid=2000 user=0
I/ActivityManager(  900): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  900): killProcessQuiet, pid=4495
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  900): Killing 4495:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1808s
W/asset   (  900): Copying FileAsset 0x6cc51c08 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  900): Recipient 4495
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  900): Skipping PackageSetting{421b3068 com.example.hello/10356} due to missing metadata
I/ActivityManager(  900): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1890): Unregistering com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
E/acms    ( 1890): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1505): Ignoring removeGeofence because network location is disabled.
D/PMS     (  900): acquireWL(434555e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1505 10028 null
D/PMS     (  900): releaseWL(434555e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1278): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "sms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "smsto"
I/Launcher( 1264): Deferring update until onResume
D/Launcher( 1264): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  900): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mmsto"
D/PackageBroadcastService( 2251): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/ActivityManager(  900): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4978 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "sms"
E/ExternalAccountType( 1328): Unsupported attribute readOnly
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "smsto"
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
W/SystemReader( 1248): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/MultiDex( 4978): install
I/MultiDex( 4978): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mmsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/MultiDex( 4978): loading existing secondary dex files
I/MultiDex( 4978): load found 1 secondary dex files
I/MultiDex( 4978): install done
D/PhoneApp( 1233): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  900): Delaying start of: ServiceRecord{4459f408 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 2251): CP2 sync disabled
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2251, uid=10028, userID:0
D/PMS     (  900): acquireWL(43fcbd28): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
I/Icing   ( 2251): doRemovePackageData com.test.thalitest
D/PMS     (  900): releaseWL(43fcbd28): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  900): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4997 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4978): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  900): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4997): install
I/MultiDex( 4997): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4997): loading existing secondary dex files
I/MultiDex( 4997): load found 1 secondary dex files
I/MultiDex( 4997): install done
I/ActivityManager(  900): Resuming delayed broadcast
I/ProviderInstaller( 4997): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1418): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  900): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1418): handle notify Blinkfeed plugin client changed
I/ActivityManager(  900): Resuming delayed broadcast
I/ActivityManager(  900): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5014 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5014, uid=10073, userID:0
D/Finsky  ( 5014): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  900): getAllNetworkInfo called by com.android.vending (5014/10073)
D/ConnectivityService(  900): getAllNetworkInfo called by com.android.vending (5014/10073)
E/SQLiteLog( 4978): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4978): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9ce610
E/DriveAsyncService( 4978): disk I/O error (code 3850)
E/DriveAsyncService( 4978): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4978): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4978): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4978): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4978): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4978): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4978): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4978): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4978): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4978): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4978): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4978): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4978): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4978): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4978): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4978): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4978): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9ce610
E/DocListDatabase( 4978): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4978): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4978): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4978): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4978): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4978): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4978): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4978): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4978): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4978): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4978): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4978): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4978): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4978): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4978): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4978): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4978): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4978): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4978): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4978): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4978): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4978): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4978): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4978): threadid=1: thread exiting with uncaught exception (group=0x41668e30)
D/Finsky  ( 5014): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
E/ActivityManager(  900): App crashed! Process: com.google.android.gms.drive
D/Process ( 4978): killProcess, pid=4978
D/Process ( 4978): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 4978): FATAL EXCEPTION: main
E/AndroidRuntime( 4978): Process: com.google.android.gms.drive, PID: 4978
E/AndroidRuntime( 4978): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4978): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4978): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4978): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4978): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4978): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4978): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4978): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4978): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4978): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4978): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4978): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4978): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4978): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4978): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4978): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4978): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4978): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4978): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4978): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4978): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4978): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4978): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4978): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4978): 	... 10 more
W/Settings( 5014): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5014): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 5014): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 5014): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5014): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5014): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5014): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 5014): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 5014): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 5014): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 5014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5014): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5014): threadid=25: thread exiting with uncaught exception (group=0x41668e30)
E/DropBoxManagerService(  900): Can't write: system_app_crash
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
I/ActivityManager(  900): Recipient 4978
W/PackageManager(  900): Unable to load service info ResolveInfo{424e7e30 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  900): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  900): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  900): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  900): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  900): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  900): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  900): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  900): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  900): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  900): 	at dalvik.system.NativeStart.main(Native Method)
E/ActivityManager(  900): App crashed! Process: com.android.vending
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Process com.google.android.gms.drive (pid 4978) has died.
E/AndroidRuntime( 5014): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 5014): Process: com.android.vending, PID: 5014
E/AndroidRuntime( 5014): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5014): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5014): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5014): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 5014): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 5014): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 5014): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5014): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5014, uid=10073, userID:0
W/ActivityManager(  900): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
D/Prism.PackageStateRece_( 1264): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 5014): killProcess, pid=5014
D/Process ( 5014): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  900): Can't write: system_app_crash
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
I/IcingCorporaProvider( 2889): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  900): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5054 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  900): Recipient 5014
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Process com.android.vending (pid 5014) has died.
E/SQLiteLog( 2889): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2889): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca217c0
W/dalvikvm( 2889): threadid=14: thread exiting with uncaught exception (group=0x41668e30)
E/ActivityManager(  900): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2889): killProcess, pid=2889
E/AndroidRuntime( 2889): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2889): Process: com.google.android.googlequicksearchbox:search, PID: 2889
E/AndroidRuntime( 2889): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2889): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2889): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2889): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2889): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2889): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2889): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2889): 	at cid.d(PG:186)
E/AndroidRuntime( 2889): 	at clo.g(PG:594)
E/AndroidRuntime( 2889): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2889): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2889): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2889): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2889): 	at clr.tL(PG:827)
E/AndroidRuntime( 2889): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2889): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2889): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2889): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  900): Can't write: system_app_crash
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
D/Process ( 2889): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
D/RemoteDisplayProvider(  900): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  900): start
W/AtomicFile(  900): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  900): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  900): Recipient 2889
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  900): Client connection lost with reason: 4
I/ActivityManager(  900): Process com.google.android.googlequicksearchbox:search (pid 2889) has died.
W/ActivityManager(  900): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 10782ms
W/ActivityManager(  900): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20782ms
D/MediaRouterService(  900): Client com.google.android.googlequicksearchbox (pid 2889): Died!
E/SQLiteDatabase( 5054): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5054): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5054): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5054): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5054): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5054): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5054): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5054): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5054): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5054): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5054): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5054): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5054): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5054): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5054): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5054): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5054): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5054): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5054): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5054): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5054): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5054): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5054): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5054): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5054): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5054): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5054): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5054): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5054): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5054): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5054): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5054): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5054): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5054): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5054): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5054): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5054): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5054): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5054): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5054): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5054): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5054): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5054): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5054): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5054): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5054): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5054): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5054): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5054): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5054): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5054): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5054): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5054): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5054): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5054): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5054): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5054): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5054): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5054): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5054): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5054): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5054): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5054): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5054): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5054): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5054): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5054): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5054): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5054): threadid=11: thread exiting with uncaught exception (group=0x41668e30)
E/ActivityManager(  900): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5054): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5054): Process: com.google.android.apps.docs, PID: 5054
E/AndroidRuntime( 5054): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5054): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5054): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5054): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5054): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5054): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5054): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5054): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5054): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  900): Can't write: system_app_crash
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop150.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
I/ActivityManager(  900): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5071 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 5054): killProcess, pid=5054
D/Process ( 5054): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Recipient 5054
I/ActivityManager(  900): Process com.google.android.apps.docs (pid 5054) has died.
W/ContextImpl( 5071): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5071): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5071): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5071): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5071): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5071): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5071): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5071): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5071): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5071): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5071): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5071): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5071): threadid=10: thread exiting with uncaught exception (group=0x41668e30)
I/ActivityManager(  900): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5084 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 5071): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5071): Process: com.android.keychain, PID: 5071
E/AndroidRuntime( 5071): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5071): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5071): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5071): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5071): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5071): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5071): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5071): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5071): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5071): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  900): App crashed! Process: com.android.keychain
D/ErrorReport(  900): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5071): killProcess, pid=5071
D/Process ( 5071): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  900): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  900): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450363269696.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  900): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  900): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  900): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  900): 	... 4 more
I/ActivityManager(  900): Recipient 5071
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Process com.android.keychain (pid 5071) has died.
W/ActivityManager(  900): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20345ms
D/AppTag  ( 5084): getInstance(Context context)
D/AppTag  ( 5084): getInstance(Context context)
D/AppTag  ( 5084): onCreate()
D/PMS     (  900): acquireWL(43a41dd0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4193 10160 null
D/PMS     (  900): releaseWL(43a41dd0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  900): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5102 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 5102): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5102 dbg=false s=true
I/DeviceManagement( 5102): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5102): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5102): WorkflowService: Starting workflow service
I/DeviceManagement( 5102): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ace358] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5102): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5102): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5102): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5102): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  900): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5116 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5102): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5102): SessionStateController: Checking invariants...
D/Documents( 5116): Loading roots for com.android.providers.downloads.documents
I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1264): loadItems() com.htc.launcher.pageview.WidgetManager@41b2be70 +
I/Prism.WidgetManager( 1264): onLoadItems() +
D/Documents( 5116): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5116): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5116): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5116): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5116): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5116): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5116): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5116): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5116): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5116): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5116): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5116): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5116): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5116): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5116): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5116): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5116): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5116): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5116): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5116): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5116): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5116): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5116): threadid=1: thread exiting with uncaught exception (group=0x41668e30)
E/AndroidRuntime( 5116): FATAL EXCEPTION: main
E/AndroidRuntime( 5116): Process: com.android.documentsui, PID: 5116
E/AndroidRuntime( 5116): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5116): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5116): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5116): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5116): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5116): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5116): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5116): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5116): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5116): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5116): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5116): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5116): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5116): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5116): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5116): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5116): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5116): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5116): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5116): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5116): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5116): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5116): 	... 10 more
I/ActivityManager(  900): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5130 uid=10023 gids={50023, 1028, 1015, 1023}
E/ActivityManager(  900): App crashed! Process: com.android.documentsui

```
