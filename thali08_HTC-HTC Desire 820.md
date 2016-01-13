#### Test 55902202f27eba5_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  907): mEventCount = 1050
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 6
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 12
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
--------- beginning of /dev/log/system
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/cutils-trace( 4469): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4469): ====startRecUseTime====
D/htc.customization.log.level( 4469):  is 
W/CustomizationLogLevel( 4469): Level value is invalid, use default level 2
D/CustomizationManager( 4469):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4469): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4469): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4469): Parsing tag category name = system
I/CustomizationCIDLoader( 4469): Parsing tag category name = application
I/CustomizationCIDLoader( 4469): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4469): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4469): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4469): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4469): Parsing tag category name = Settings
D/CustomizationManager( 4469):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4469):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4469): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4469): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4469): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4469): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4469
D/PMS     (  907): acquireHCC(4252b708): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(424510b0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x65600ed8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1112194352
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b70968
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
D/PMS     (  907): acquireWL(423c48c0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4480 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1268): [trimMemory] 20
W/asset   ( 4480): Copying FileAsset 0x5c731428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4480): Binding Chromium to main looper Looper (main, tid 1) {41ab3608}
I/LibraryLoader( 4480): Expected native library version number "",actual native library version number ""
I/chromium( 4480): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4480): Initializing chromium process, renderers=0
D/WIFI_ICON( 1116): WifiActivity: 1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PMS     (  907): acquireWL(42023de8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(41f92d70): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4252e740:true
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  907): releaseWL(42023de8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4480): 1101828160: getState(). Returning 12
I/Adreno-EGL( 4480): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4480): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4480): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4480): Local Branch: 
I/Adreno-EGL( 4480): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4480): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4480):                  aa63bbd948f41d15fc72f585e
W/chromium( 4480): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4480): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4480): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4480): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4480): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4480): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4480): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4480): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4480): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4480): CordovaWebView is running on device made by: HTC
,W/AwContents( 4480): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1268
,W/ResourceType( 4480): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4480): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41afa6f0, mServedView=org.apache.cordova.engine.SystemWebView{41ac0358 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  907): Enable input method client, pid=4480
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4480): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +282ms
D/PMS     (  907): releaseWL(423c48c0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4480): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4480): JniHelper::setJavaVM(0x41588048), pthread_self() = 1662336688
,D/JX-Cordova( 4480): jxcore cordova android initializing
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 11.541MB for 63974-byte allocation
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 11.598MB for 95956-byte allocation
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 11.682MB for 143930-byte allocation
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 11.802MB for 215890-byte allocation
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 11.959MB for 323830-byte allocation
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 12.625MB for 728606-byte allocation
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 13.218MB for 1092904-byte allocation
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 14.102MB for 1639352-byte allocation
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 6
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 18
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 15.445MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(4252b708): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(424510b0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4480): Grow heap (frag case) to 17.448MB for 3688532-byte allocation
,W/jxcore-log( 4480): Initializing JXcore engine
,W/jxcore-log( 4480): JXcore engine is ready
,W/jxcore-log( 4480): Starting JXcore engine
,W/jxcore-log( 4480): Platform android
W/jxcore-log( 4480): 
,W/jxcore-log( 4480): Process ARCH arm
W/jxcore-log( 4480): 
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{441ae7e0 u0 com.htc.htclocationservice/.AutoSettingService}
,I/jxcore-log( 4480): JXcore Cordova bridge is ready!
I/jxcore-log( 4480): 
,W/jxcore-log( 4480): JXcore engine is started
,I/chromium( 4480): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/PMS     (  907): releaseWL(41f92d70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4480): Toggling radios to true
I/jxcore-log( 4480): 
,D/BluetoothAdapter( 4480): enable(): BT is already enabled..!
,D/WifiManager( 4480): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1448
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
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
D/WifiManager( 4480): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiManager( 4480): reconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): TDLS: Tear down peers
I/wpa_supplicant( 1155): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4480): Radios toggled
I/jxcore-log( 4480): 
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4480, uid=10189
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4480): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4480): 
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1155): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1155): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1155): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb732cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1155): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1155): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/Tethering(  907): [isWifi] getHotspotEnabled: false
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
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(42546b30): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/wpa_supplicant( 1155): Fast associate: Old scan results
I/wpa_supplicant( 1155): wpa_supplicant_scan enter
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1155): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19569 mDataStallAlarmIntent=PendingIntent{41dd6d90: PendingIntentRecord{42571910 android broadcastIntent}}
,D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4306): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/libc    (  363): [NET] entry_id:6   entry:0xb8710fd8  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb87118f8  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8711258  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8711310  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8711428  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb87117d0  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb87110e8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb87114f0  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb8710d90  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/PMS     (  907): acquireWL(425606f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(424d2130): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WISPrService( 4306): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WISPrService( 4306): >>>>>WISPrService start isConnected = false<<<<<
D/WifiNative-wlan0(  907):    returned false
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4306): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1371/10028)
D/PMS     (  907): acquireWL(4320e1f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  907): releaseWL(425606f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
,D/PMS     (  907): releaseWL(4320e1f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:2
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  907): releaseWL(424d2130): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 3943): type=WIFI subType= reason=null isConnected=false
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3943/10154)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(42e5a100): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(42e5a100): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1890/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4369/10100)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4369/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2464/10021)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4533 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4533): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4533): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4533): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4533): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4533): Preparing secondary program dexes.
V/DexLibLoader( 4533): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4533): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4533): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4533): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4533): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4533): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4533): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4533): Dex already copied
D/OdexVerifier( 4533): Odex verification is skipped.
,V/DexLibLoader( 4533): Creating class loader
,V/DexLibLoader( 4533): Finished creating class loader
V/DexLibLoader( 4533): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4533): Dex already copied
D/OdexVerifier( 4533): Odex verification is skipped.
,V/DexLibLoader( 4533): Creating class loader,
,V/DexLibLoader( 4533): Finished creating class loader
V/DexLibLoader( 4533): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4533): Dex already copied
D/OdexVerifier( 4533): Odex verification is skipped.
,V/DexLibLoader( 4533): Creating class loader,
V/DexLibLoader( 4533): Finished creating class loader
V/DexLibLoader( 4533): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4533): Dex already copied
,D/OdexVerifier( 4533): Odex verification is skipped.
,V/DexLibLoader( 4533): Creating class loader
,V/DexLibLoader( 4533): Finished creating class loader
,V/DexLibLoader( 4533): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4533): DexLibLoader.ensureDexLoaded took 16 ms
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4545 uid=10077 gids={50077}
D/PMS     (  907): acquireWL(43267788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
,V/AlarmManager(  907): sending alarm PendingIntent{42485b08: PendingIntentRecord{423bfba0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452699354895, Int=60000
,D/PMS     (  907): releaseWL(43267788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4545): SMSBackupAgentService started
,D/SMSBackup( 4545): Checking restore status
D/SMSBackup( 4545): Restore complete
,D/SMSBackup( 4545): cancelCheckAlarm
,D/SMSBackup( 4545): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  907): killProcessQuiet, pid=4162
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4162:com.google.android.apps.genie.geniewidget/u0a106 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4162
,D/PMS     (  907): acquireWL(43b96870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  907): acquireWL(43c393a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  907): releaseWL(43b96870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(43c393a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/dalvikvm( 4533): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4533): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4533): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4533): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4533): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4533): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4533): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4533): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1155): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1155): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1155): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 3
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 1
I/wpa_supplicant( 1155): wpa_s->is_screen_on 1
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): selected network = 1
D/wpa_supplicant( 1155): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb732e4e8  current_ssid=0x0
D/wpa_supplicant( 1155): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1155): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1155): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1155): check if in concurrent case
,I/wpa_supplicant( 1155): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
,D/wpa_supplicant( 1155): wpa_supplicant_associate, 1777,
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1795,
D/wpa_supplicant( 1155): RSN: PMKSA cache search - network_ctx=0xb732e4e8 try_opportunistic=0
D/wpa_supplicant( 1155): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1155): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1155): State: SCANNING -> ASSOCIATING,
,D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1155): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1155): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1155): nl80211: Unsubscribe mgmt frames handle 0xb732d718 (mode change)
D/wpa_supplicant( 1155): nl80211: Subscribe to mgmt frames with non-AP handle 0xb732d718
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb732d718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1155):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1155):   * freq=2412
D/wpa_supplicant( 1155):   * Auth Type 0
D/wpa_supplicant( 1155):   * WPA Versions 0x2
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1155): nl80211: Connect request send successfully
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000021601441
,I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000104601279
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000104601283
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000104601273
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 21601441, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 104601279, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 104601283, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 104601273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/dalvikvm( 4533): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Connect event
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1155): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1155): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1155): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): TDLS: Remove peers on association
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1155): EAPOL: enable timer tick
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1155): Get randomness: len=32 entropy=5
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWit,hEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb732d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f84b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1155):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1155): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1155): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1155): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1155): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1155): set send_ind_to_ndc = 0
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1155): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1155): EAPOL authentication completed successfully
I/wpa_supplicant( 1155): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
E/FbInjectorInitializer( 4533): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WISPrService( 4306): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4306): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 1
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  907):    returned null
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(4320d668): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423b6950 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423b6950 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4533): Verify
,D/PMS     (  907): acquireWL(44000208): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/PMS     (  907): releaseWL(44000208): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(438c0610): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/WifiService(  907): New client listening to asynchronous messages
,D/PMS     (  907): releaseWL(438c0610): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4533): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4533): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=3925
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3925:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  907): acquireWL(43085430): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1224 10028 null
,D/PMS     (  907): acquireWL(440ffe08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1224 10028 null
,D/PMS     (  907): releaseWL(43085430): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,D/PMS     (  907): releaseWL(440ffe08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,D/AutoSetting( 1417): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4580 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1417/10053)
,D/AutoSetting( 1417): Util - no network available!
,D/AutoSetting( 1417): service - onCreate()
,D/AutoSetting( 1417): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  907): request 424eaa90 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1417/10053)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1417): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1417): service - mHandler: cancel location update
D/AutoSetting( 1417): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4533): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4533): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
I/ActivityManager(  907): Recipient 3925
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4533): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4580): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4580): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4596 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4533): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4613 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4047
,I/ActivityManager(  907): Killing 4047:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/dalvikvm( 4533): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4533): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4533): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4533): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4533): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4533): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 9.963MB for 84664-byte allocation
E/dalvikvm( 4533): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4533): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4533): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4533): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4533): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4533): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4533): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4533): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4613): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 9.977MB for 28144-byte allocation
E/dalvikvm( 4533): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4533): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4533): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4533): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/ActivityManager(  907): Recipient 4047
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 10.017MB for 39954-byte allocation
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 10.092MB for 79892-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4613/10151)
,V/WebViewChromiumFactoryProvider( 4613): Binding Chromium to main looper Looper (main, tid 1) {41ab8250}
,I/LibraryLoader( 4613): Expected native library version number "",actual native library version number ""
,I/chromium( 4613): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4613): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4613): BLUETOOTH permission is missing!
D/PMS     (  907): acquireWL(43c60508): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(42569c98): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): releaseWL(43c60508): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4613): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4613): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4613): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4613): Local Branch: 
I/Adreno-EGL( 4613): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4613): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4613):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4613): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4613/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4613/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4201/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4201/10160)
,D/Process (  907): killProcessQuiet, pid=4278
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4278:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/dalvikvm-heap( 4533): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,I/ActivityManager(  907): Recipient 4278
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4360eea0 u0 ReceiverList{434f2860 4533 com.facebook.katana/10026/u0 remote:43370370}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4360eea0 u0 ReceiverList{434f2860 4533 com.facebook.katana/10026/u0 remote:43370370}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42401828 u0 ReceiverList{424017c8 4533 com.facebook.katana/10026/u0 remote:4409e890}}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,D/PMS     (  907): acquireWL(436125d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  907): releaseWL(436125d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1430): Unknown pending intent to remove.
D/PMS     (  907): acquireWL(43ba5188): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
D/PMS     (  907): releaseWL(43ba5188): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1155): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1155): EAPOL: disable timer tick
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4533): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4533): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/SensorManager(  907): mEventCount = 1200
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(4320d668): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1155): Change stage from stage0 to stage3
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1155): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19571 delay=15s
,D/WifiWatchdogStateMachine(  907): WAN detection
,D/WISPrService( 4306): >>>>>WISPrService start isConnected = true<<<<<
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
,D/MDST    (  907): default: setEnableApn apnType =default , enable=false,
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0,
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@423e23d8
,D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(4385c340): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
,D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
,D/PMS     (  907): acquireWL(43699cf0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1224 10028 null
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  907): acquireWL(425f7440): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1224 10028 null
D/PMS     (  907): releaseWL(43699cf0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/CheckinService( 1224): Preparing to send checkin request
,I/EventLogService( 1224): Accumulating logs since 1452699308367
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1224): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1224): Using GMS GoogleHttpClient
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1224/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1224/10028)
,D/PMS     (  907): releaseWL(4385c340): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 1224): awaiting user notification for token
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b408b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 7 2 12
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4688 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4688): install
,I/MultiDex( 4688): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4688): loading existing secondary dex files
,I/MultiDex( 4688): load found 1 secondary dex files
,I/MultiDex( 4688): install done
,I/ProviderInstaller( 4688): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4688/10028)
,W/Settings( 4688): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4688): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4688): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4688): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4688): Local Branch: 
I/Adreno-EGL( 4688): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4688): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4688):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-57 , oldRssi= -200
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/Adreno-EGL( 4688): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4688): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4688): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4688): Local Branch: 
I/Adreno-EGL( 4688): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4688): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4688):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1116): WifiActivity: 3
,I/Adreno-EGL( 4688): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4688): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4688): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4688): Local Branch: 
I/Adreno-EGL( 4688): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4688): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4688):                  aa63bbd948f41d15fc72f585e
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  907): releaseWL(42546b30): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  907): bSetPropertyMultiRAB:false
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): CONNECTED
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/PMS     (  907): acquireWL(43b27bd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4369/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1890/1000)
,D/CaptivePortalTracker(  907): NoActiveNetworkState
I/acms    ( 1890): Checking Certificates
I/acms    ( 1890): Checking Developer Certificates
I/acms    ( 1890): Checking Application Certificates
I/acms    ( 1890): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1890): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1890): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1890): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1890): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1890): Updating next query delay: 75600000
I/mlserverapp( 1890): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1890): cancelACMSProgrammedChecks
,I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3943): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3943/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3965/10051)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4369/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2464/10021)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(424b3520): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1224 10028 null
,D/PMS     (  907): releaseWL(424b3520): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
,W/fb4a(:<default>):UserScope( 4533): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4533): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1371): [NET] getaddrinfo-,err=8
D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1371): [NET] getaddrinfo-, 1
D/libc    ( 1371): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
,D/PMS     (  907): acquireWL(41ab96e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1371 10028 null
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =114a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/AutoSetting( 1417): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,D/AutoSetting( 1417): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1417): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1417): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1417): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1417): service - handleMessage() setting current location null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1417/10053)
D/PMS     (  907): releaseWL(43b27bd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4613/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(424a5538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/AutoSetting( 1417): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1417): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1417/10053)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4201/10160)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4201/10160)
D/PMS     (  907): acquireWL(440b19d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 226
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1371): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  907): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4716 uid=10106 gids={50106, 3003, 5012}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4201): Grow heap (frag case) to 13.518MB for 1821008-byte allocation
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
,D/PMS     (  907): releaseWL(424a5538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1371): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): acquireWL(430e3610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  907): releaseWL(430e3610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1371): Connected
D/PMS     (  907): acquireWL(43c5f480): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): releaseWL(41ab96e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
,I/NewsWeather( 4716): LocationClient connecting
D/PMS     (  907): releaseWL(43c5f480): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(42358238): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1371): Message class mpf
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): releaseWL(42358238): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(43fd0f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  907): releaseWL(43fd0f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/NewsWeather( 4716): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4716): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4716): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4716): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4716): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4716): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,E/fb4a(:<default>):LocalFbBroadcastManager( 4533): Called registerBroadcastReceiver twice.
,I/CheckinTask( 1224): Sending checkin request (9018 bytes)
D/libc    ( 1224): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
D/libc    ( 1224): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5b3c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 233
,D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,I/ProviderInstaller( 4716): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(425a7598): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
I/NewsWeather( 4716): Last usage 0, idle 1452699359s, sync interval 2592000s
,I/NewsWeather( 4716): setPeriodicSync in seconds 2592000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,D/PMS     (  907): releaseWL(425a7598): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,I/NewsWeather( 4716): onConnected null
D/libc    ( 1224): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/PMS     (  907): acquireWL(425d7c60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/PMS     (  907): acquireWL(43227468): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,W/GCoreFlp( 1430): No location to return for getLastLocation()
,I/NewsWeather( 4716): LocationClient onConnected: location null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/PMS     (  907): releaseWL(425d7c60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/PMS     (  907): releaseWL(43227468): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
I/NewsWeather( 4716): Skip sync for lookup editions
,I/NewsWeather( 4716): syncNewsAppData traffic type BACKGROUND_POLL
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,I/NewsWeather( 4716): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c03bc0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4716): Unrecoverable authentication exception
E/NewsWeather( 4716): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4716): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 7 2 12
,D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4716): [NET] getaddrinfo-,err=8
D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4716): [NET] getaddrinfo-, 1
D/libc    ( 4716): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b360 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  907): releaseWL(42569c98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=70
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4716): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4716): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/NewsWeather( 4716): Failed to syncNewsAppData
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
E/NewsWeather( 4716): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=10 [28][3][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(42521518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  907): releaseWL(42521518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43a2e780): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 70293, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(440b19d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/PMS     (  907): releaseWL(43a2e780): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  907): killProcessQuiet, pid=4335
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  907): Killing 4335:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4322fc68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/ActivityManager(  907): Recipient 4335
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): releaseWL(4322fc68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(425cfe68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  907): releaseWL(425cfe68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1224/10028)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1224/10028)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1224): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41cd48e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 0 6 2 12
,I/CheckinTask( 1224): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1224): Unable to close GMS GoogleHttpClient
D/PMS     (  907): acquireWL(43bc3518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b7e268: PendingIntentRecord{41b7e120 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=108876, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43bc3518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  907): releaseWL(425f7440): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1224): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b3eb08 that was originally bound here
E/ActivityThread( 1224): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b3eb08 that was originally bound here
E/ActivityThread( 1224): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1224): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1224): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1224): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1224): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1224): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1224): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1224): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1224): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1224): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1224): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1224): 	at bks.a(SourceFile:298)
E/ActivityThread( 1224): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1224): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1224): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1224): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1371): GCM config loaded
,I/ClockThread( 1116): now=1452699360053 next=59947
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =71db +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/72.247.98.119
,I/GAV2    ( 4613): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 4480): Test app app.js loaded
I/jxcore-log( 4480): 
,I/Choreographer( 4480): Skipped 535 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4480): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV4    ( 4716): Thread[GAThread,5,main]: No campaign data found.
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42158420
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42158420, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42313820
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@42594e20
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,W/PMS     (  907): mWirelessDisplayManager is null
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/Process (  907): killProcessQuiet, pid=4369
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4369:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4369
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 379ms
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43586a90)
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
D/PMS     (  907): nativeSetInteractive:false
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=4480
D/PMN     (  907): wakingUp
,D/NfcService( 1254): applyRouting -2
W/ResourceType( 4480): No package identifier when getting name for resource number 0x00000064
V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
,I/InputMethodManager( 4480): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ac0358 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  907): acquireWL(43aea938): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  907): releaseWL(43aea938): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
,D/PMN     (  907): onScreenOn
I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/PMS     (  907): acquireWL(44053ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(44053ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/MtpService( 2464): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2464): [MTP][onReceive]-
,D/AutoSetting( 1417): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1254): applyRouting - 0
D/NfcService( 1254): applyRouting -2
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): acquireWL(43bf52b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,D/PMS     (  907): releaseWL(43bf52b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
V/NotificationService(  907): batLight: Full, plugged
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/AutoSetting( 1417): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19572 delay=15s
I/ClockThread( 1116): stop update clock
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:On
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): BG scan when screen On
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): Match BG scan, scan!
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
D/TetherSettings( 4306): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4306): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4306): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4306): Cust_ConnectToPC   : spcsc>false
D/        ( 4306): Cust_ConnectToPC   : IPT>true
D/        ( 4306): Cust_ConnectToPC   : Singel_USB>false
D/WifiNative-wlan0(  907):    returned true
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,W/Settings( 4306): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4306): hasRemovableStorageSlot: true
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/SmartNS_Utility( 4306): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4306): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4306): onReceive:android.intent.action.USER_PRESENT
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  907): updateScreenOn: false
,I/SmartNS_PSService( 4306): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4306): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4306):  defaultType:0
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4760 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(43676ba8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): onScreenOn: 1452699364915
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1794): onScreenOn: 1452699364915
D/PMS     (  907): releaseWL(43676ba8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42313820
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [7][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42313820, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@42594e20
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
D/PMN     (  907): goingToSleep
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:48, mTXpacketCount:0, avgLinkspeed:24,mAvgTxRate54
D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  907): acquireWL(4360eb20): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4360eb20): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19572 mDataStallAlarmIntent=PendingIntent{43c016f0: PendingIntentRecord{42571910 android broadcastIntent}}
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:Off
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1155): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
W/ContextImpl( 4760): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(434eccc8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,D/NetworkPolicy(  907): updateScreenOn: false
D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/SmartSyncUtils( 4760): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(4363f058): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4760 1000 null
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(434eccc8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4760): getMobilePolicyEnabled, result = true
,D/Process (  907): killProcessQuiet, pid=4385
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(4363f058): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Killing 4385:com.htc.backup/1000 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PhoneStatusBar( 1116): removeHeadsNotification.gc: 52
I/ActivityManager(  907): Recipient 4385
,W/ContextImpl( 4760): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4760): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4760): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4760): isEpsOn(), nState = 0
D/WifiService(  907): New client listening to asynchronous messages
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] getTotalRam: 1873 Mb
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42594e20
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42594e20, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): onScreenOff.
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42594e20, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1794): onScreenOff
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42594e20
D/PMS     (  907): acquireWL(43c68930): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
D/PMS     (  907): releaseWL(43c68930): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@428197d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@428197d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/AutoSetting( 1417): service - mHandler: cancel location update
D/AutoSetting( 1417): service -           changes count: 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 10.955MB for 24676-byte allocation
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 11.002MB for 55510-byte allocation
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 11.008MB for 43014-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4533/10026)
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 11.057MB for 65540-byte allocation
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 11.077MB for 56822-byte allocation
,D/libc    ( 4533): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4533): [NET] getaddrinfo-,err=8
D/libc    ( 4533): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4533): [NET] getaddrinfo-, 1
,D/libc    ( 4533): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2695 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 46
D/libc    (  363): [NET]res_nsend:resplen=93
D/libc    (  363): [NET]res_queryN: exit 3, ancount=3
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4533): [NET] getaddrinfo_proxy-, success
I/global  ( 4533): call createSocket() return a new socket.
D/libc    ( 4533): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4533): [NET] getaddrinfo-, SUCCESS
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=11 entropy=0
D/wpa_supplicant( 1155): Add randomness: count=12 entropy=1
D/wpa_supplicant( 1155): Add randomness: count=13 entropy=2
D/wpa_supplicant( 1155): Add randomness: count=14 entropy=3
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-5,7
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=15 entropy=4
D/wpa_supplicant( 1155): Add randomness: count=16 entropy=5
D/wpa_supplicant( 1155): Add randomness: count=17 entropy=6
D/wpa_supplicant( 1155): Add randomness: count=18 entropy=7
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43ac7d90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000116631473
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000116631510,
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000116631520
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
,I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000116631499
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/libc    ( 4533): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4533): [NET] getaddrinfo-,err=8
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43ac7d90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@43ac7d90 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 116631473, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 116631510, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 116631520, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 116631499, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43baec50): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4533 10026 null
,D/AutoSetting( 1508): service - handleMessage() stop self
,D/AutoSetting( 1508): service - handleMessage() quit looper
,D/AutoSetting( 1508): service - onDestroy() END
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4533): I/O error closing connection
I/global  ( 4533): java.net.SocketException: Socket is closed
I/global  ( 4533): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4533): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4533): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4533): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4533): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4533): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4533): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4533): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4533): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4533): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4533): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4533): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4533): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4533): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4533): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4533): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4533): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4533): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4533): Removing a connection that never existed!
D/PMS     (  907): releaseWL(43baec50): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{41ccfde0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/Process (  907): killProcessQuiet, pid=3965
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3965:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3965
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(43ae3678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/PMS     (  907): acquireWL(43ad9bb0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{41d6e210: PendingIntentRecord{42454c70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=131054, Int=0
D/PMS     (  907): releaseWL(43ae3678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43a82da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43ad9bb0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(43a82da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(4363ed00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/PMS     (  907): releaseWL(4363ed00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck,
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-83
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=19 entropy=8
D/wpa_supplicant( 1155): Add randomness: count=20 entropy=9
D/wpa_supplicant( 1155): Add randomness: count=21 entropy=10
D/wpa_supplicant( 1155): Add randomness: count=22 entropy=11
D/wpa_supplicant( 1155): Add randomness: count=23 entropy=12
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-83
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=24 entropy=13
D/wpa_supplicant( 1155): Add randomness: count=25 entropy=14
D/wpa_supplicant( 1155): Add randomness: count=26 entropy=15
,D/wpa_supplicant( 1155): Add randomness: count=27 entropy=16
D/wpa_supplicant( 1155): Add randomness: count=28 entropy=17
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  907): getDiscoveryDongleList
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1155): reply (631) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000134933669
,I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000134933706
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000134933716
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57,
I/wpa_supplicant( 1155): tsf=0000000134933695
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-83
I/wpa_supplicant( 1155): tsf=0000000134933726
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 134933669, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 134933706, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 134933716, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 134933695, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -83, frequency: 2437, timestamp: 134933726, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-83], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/AutoSetting( 1417): service - mHandler: update timezone
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1508): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1589): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1508): service - mHandler: update timezone
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1508): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1508): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1116): removeNotification.gc:55
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b408b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 6 2 11
,D/AutoSetting( 1417): service - handleMessage() stop self
,D/AutoSetting( 1417): service - handleMessage() quit looper
,D/AutoSetting( 1417): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4356
,I/ActivityManager(  907): Killing 4356:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4356
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43592d10 u0 com.htc.htclocationservice/.AutoSettingService}
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=29 entropy=18
D/wpa_supplicant( 1155): Add randomness: count=30 entropy=19
D/wpa_supplicant( 1155): Add randomness: count=31 entropy=20
D/wpa_supplicant( 1155): Add randomness: count=32 entropy=21
D/wpa_supplicant( 1155): Add randomness: count=33 entropy=22
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1155): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=34 entropy=23
D/wpa_supplicant( 1155): Add randomness: count=35 entropy=24
D/wpa_supplicant( 1155): Add randomness: count=36 entropy=25
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): Add randomness: count=37 entropy=26
,D/wpa_supplicant( 1155): Add randomness: count=38 entropy=27
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1155): reply (916) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000153233353
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
,I/wpa_supplicant( 1155): tsf=0000000153233447
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000153233461
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000134933695
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-83
I/wpa_supplicant( 1155): tsf=0000000134933726
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5,
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000153233471
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000153233483
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 153233353, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 153233447, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 153233461, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 134933695, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -83, frequency: 2437, timestamp: 134933726, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 153233471, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 153233483, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 7 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-83], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq:  9 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425a9e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  907): sending alarm PendingIntent{4236cfa8: PendingIntentRecord{42484cf8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141057, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{43bf06e0: PendingIntentRecord{420b4088 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144006, Int=0
D/PMS     (  907): acquireWL(42359e98): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
V/AlarmManager(  907): sending alarm PendingIntent{41d6e210: PendingIntentRecord{42454c70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=161074, Int=0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): acquireWL(424f3190): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): acquireWL(42fb6680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  907): releaseWL(425a9e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =75ed +++++,
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  907): releaseWL(42fb6680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425a07b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=9 [43][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43c73ba8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,D/PMS     (  907): releaseWL(424f3190): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(425a07b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42600aa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/NewsWeather( 4716): Last usage 0, idle 1452699412s, sync interval 2592000s
,I/NewsWeather( 4716): setPeriodicSync in seconds 2592000
D/PMS     (  907): releaseWL(42600aa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,I/NewsWeather( 4716): Skip sync for lookup editions
,I/NewsWeather( 4716): syncNewsAppData traffic type BACKGROUND_POLL
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,I/NewsWeather( 4716): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4716): Unrecoverable authentication exception
E/NewsWeather( 4716): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4716): ,	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c030b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 13 5 12
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): acquireWL(43aaa938): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,E/NewsWeather( 4716): Failed to syncNewsAppData
,E/NewsWeather( 4716): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(43aaa938): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4259f3c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 108743, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(43c73ba8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1430/10028)
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(4259f3c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42e187b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42e187b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,D/PMS     (  907): releaseWL(42359e98): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/AutoSetting( 1508): service - handleMessage() stop self
,D/AutoSetting( 1508): service - onDestroy() END
,D/AutoSetting( 1508): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4408
,I/ActivityManager(  907): Killing 4408:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4408
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(43133a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b7e268: PendingIntentRecord{41b7e120 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=168876, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43133a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=39 entropy=28
D/wpa_supplicant( 1155): Add randomness: count=40 entropy=29
D/wpa_supplicant( 1155): Add randomness: count=41 entropy=30
D/wpa_supplicant( 1155): Add randomness: count=42 entropy=31
D/wpa_supplicant( 1155): Add randomness: count=43 entropy=32
D/wpa_supplicant( 1155): Add randomness: count=44 entropy=33
D/wpa_supplicant( 1155): Add randomness: count=45 entropy=34
D/wpa_supplicant( 1155): Add randomness: count=46 entropy=35
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1,155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 7: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=47 entropy=36
D/wpa_supplicant( 1155): Add randomness: count=48 entropy=37
D/wpa_supplicant( 1155): Add randomness: count=49 entropy=38
D/wpa_supplicant( 1155): Add randomness: count=50 entropy=39
D/wpa_supplicant( 1155): Add randomness: count=51 entropy=40
D/wpa_supplicant( 1155): Add randomness: count=52 entropy=41
D/wpa_supplicant( 1155): Add randomness: count=53 entropy=42
D/wpa_supplicant( 1155): Add randomness: count=54 entropy=43
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1100) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000171494014
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
,I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000171494042
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000171494054
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-82
I/wpa_supplicant( 1155): tsf=0000000171494063
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
,I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000171494075
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000171494107
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
,I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000171494096
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 171494014, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 171494042, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 171494054, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P], level: -82, frequency: 2437, timestamp: 171494063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 171494075, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  907): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 171494107, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 171494096, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 171494084, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 8 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-82], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq:  9 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (8) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
,D/PMS     (  907): acquireWL(430e4d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(430e4d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=55 entropy=44
D/wpa_supplicant( 1155): Add randomness: count=56 entropy=45
D/wpa_supplicant( 1155): Add randomness: count=57 entropy=46
D/wpa_supplicant( 1155): Add randomness: count=58 entropy=47
D/wpa_supplicant( 1155): Add randomness: count=59 entropy=48
D/wpa_supplicant( 1155): Add randomness: count=60 entropy=49
D/wpa_supplicant( 1155): Add randomness: count=61 entropy=50
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 ,series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=62 entropy=51
D/wpa_supplicant( 1155): Add randomness: count=63 entropy=52
D/wpa_supplicant( 1155): Add randomness: count=64 entropy=53
D/wpa_supplicant( 1155): Add randomness: count=65 entropy=54
D/wpa_supplicant( 1155): Add randomness: count=66 entropy=55
D/wpa_supplicant( 1155): Add randomness: count=67 entropy=56
D/wpa_supplicant( 1155): Add randomness: count=68 entropy=57
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
,I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1100) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000189723630
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000189723656
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000189723667
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-82
I/wpa_supplicant( 1155): tsf=0000000171494063
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000189723677
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000189723709
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-87
I/wpa_supplicant( 1155): tsf=0000000189723699
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 189723630, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 189723656, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 189723667, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P], level: -82, frequency: 2437, timestamp: 171494063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 189723677, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 189723709, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 189723699, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 189723688, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 8 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-82], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq:  9 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (8) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(436fbc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/PMS     (  907): acquireWL(440b0688): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{41d6e210: PendingIntentRecord{42454c70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=191158, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(436fbc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(434dcce8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(44107940): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 907 1000 WorkSource{10160}
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=10 [39][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(440b0688): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(434dcce8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/dalvikvm-heap( 4201): Grow heap (frag case) to 15.217MB for 1821008-byte allocation
,I/dalvikvm-heap( 4201): Grow heap (frag case) to 16.947MB for 1821008-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43ac5fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43ac5fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(440aeb78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(440aeb78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42a131d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(44107940): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  907): releaseWL(42a131d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(43c5b670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43c5b670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=69 entropy=58
D/wpa_supplicant( 1155): Add randomness: count=70 entropy=59
D/wpa_supplicant( 1155): Add randomness: count=71 entropy=60
D/wpa_supplicant( 1155): Add randomness: count=72 entropy=61
D/wpa_supplicant( 1155): Add randomness: count=73 entropy=62
D/wpa_supplicant( 1155): Add randomness: count=74 entropy=63
D/wpa_supplicant( 1155): Add randomness: count=75 entropy=64
D/wpa_supplicant( 1155): Add randomness: count=76 entropy=65
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_sc,reen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 7: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=77 entropy=66
D/wpa_supplicant( 1155): Add randomness: count=78 entropy=67
D/wpa_supplicant( 1155): Add randomness: count=79 entropy=68
D/wpa_supplicant( 1155): Add randomness: count=80 entropy=69
D/wpa_supplicant( 1155): Add randomness: count=81 entropy=70
D/wpa_supplicant( 1155): Add randomness: count=82 entropy=71
D/wpa_supplicant( 1155): Add randomness: count=83 entropy=72
D/wpa_supplicant( 1155): Add randomness: count=84 entropy=73
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1213) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000207963757
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000207963797
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000207963808
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-82
I/wpa_supplicant( 1155): tsf=0000000207963817
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000207963839
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000189723709
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=dc:4a:3e:0f:c2:f1,
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-87
I/wpa_supplicant( 1155): tsf=0000000207963848
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 207963757, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 207963797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 207963808, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P], level: -82, frequency: 2437, timestamp: 207963817, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 207963839, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 189723709, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 207963848, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 207963829, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,D/WifiStateMachine(  907): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 207963785, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-82], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq:  9 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425c5f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/PMS     (  907): acquireWL(43531dc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{41d6e210: PendingIntentRecord{42454c70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=221233, Int=0
D/PMS     (  907): releaseWL(425c5f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42bafb10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43531dc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42bafb10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(41daab48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{4234f298: PendingIntentRecord{43921608 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=225643, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{43070f90: PendingIntentRecord{42f07910 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452699462261, Int=84918423
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4802 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{424f8c78: PendingIntentRecord{42490a28 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452699471805, Int=10800000
,D/PMS     (  907): releaseWL(41daab48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,D/SnetService( 1224): snet destroyed
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4802/10047)
,D/Process (  907): killProcessQuiet, pid=4427
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4427:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4427
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=85 entropy=74
D/wpa_supplicant( 1155): Add randomness: count=86 entropy=75
D/wpa_supplicant( 1155): Add randomness: count=87 entropy=76
D/wpa_supplicant( 1155): Add randomness: count=88 entropy=77
D/wpa_supplicant( 1155): Add randomness: count=89 entropy=78
D/wpa_supplicant( 1155): Add randomness: count=90 entropy=79
D/wpa_supplicant( 1155): Add randomness: count=91 entropy=80
D/wpa_supplicant( 1155): Add randomness: count=92 entropy=81
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wp,a_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 7: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
,I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=8/32 last_scan_full=0
,D/wpa_supplicant( 1155): Add randomness: count=93 entropy=82
D/wpa_supplicant( 1155): Add randomness: count=94 entropy=83
D/wpa_supplicant( 1155): Add randomness: count=95 entropy=84
D/wpa_supplicant( 1155): Add randomness: count=96 entropy=85
D/wpa_supplicant( 1155): Add randomness: count=97 entropy=86
D/wpa_supplicant( 1155): Add randomness: count=98 entropy=87
D/wpa_supplicant( 1155): Add randomness: count=99 entropy=88
D/wpa_supplicant( 1155): Add randomness: count=100 entropy=89
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1338) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000207963757
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000226042127
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000226042137
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-82
I/wpa_supplicant( 1155): tsf=0000000207963817
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5,
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000226042147
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000226042180
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-87
I/wpa_supplicant( 1155): tsf=0000000226042158
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 207963757, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 226042127, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 226042137, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P], level: -82, frequency: 2437, timestamp: 207963817, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 226042147, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 226042180, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 226042158, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 207963829, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 226042116, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 9: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 226042168, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 10 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  74, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  7 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-82], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq:  7 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  67, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (10) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,D/PMS     (  907): acquireWL(43586708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b7e268: PendingIntentRecord{41b7e120 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=228877, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43586708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43bb4248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{43b4bf00: PendingIntentRecord{43921608 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=233872, Int=0
,D/PMS     (  907): releaseWL(43bb4248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  907): acquireWL(43b1ebb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b1ebb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-81
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=101 entropy=90
D/wpa_supplicant( 1155): Add randomness: count=102 entropy=91
D/wpa_supplicant( 1155): Add randomness: count=103 entropy=92
D/wpa_supplicant( 1155): Add randomness: count=104 entropy=93
D/wpa_supplicant( 1155): Add randomness: count=105 entropy=94
D/wpa_supplicant( 1155): Add randomness: count=106 entropy=95
D/wpa_supplicant( 1155): Add randomness: count=107 entropy=96
D/wpa_supplicant( 1155): Add randomness: count=108 entropy=97
D/wpa_supplicant( 1155): Add randomness: count=109 entropy=98
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/,wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 7: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 8: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-81
I/wpa_supplicant( 1155): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=110 entropy=99
D/wpa_supplicant( 1155): Add randomness: count=111 entropy=100
D/wpa_supplicant( 1155): Add randomness: count=112 entropy=101
D/wpa_supplicant( 1155): Add randomness: count=113 entropy=102
D/wpa_supplicant( 1155): Add randomness: count=114 entropy=103
D/wpa_supplicant( 1155): Add randomness: count=115 entropy=104
D/wpa_supplicant( 1155): Add randomness: count=116 entropy=105
D/wpa_supplicant( 1155): Add randomness: count=117 entropy=106
D/wpa_supplicant( 1155): Add randomness: count=118 entropy=107
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/,wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1155): reply (1186) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000244313769
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000244313807
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000244313817
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_s,upplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000244313827
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000226042147
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000244313868
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-87
I/wpa_supplicant( 1155): tsf=0000000244313858
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 244313769, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 244313807, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 244313817, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -81, frequency: 2437, timestamp: 244313827, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 226042147, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 244313868, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 244313858, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 244313796, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 244313839, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-81], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  74, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  7 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq:  7 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(435870b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41d6e210: PendingIntentRecord{42454c70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=251256, Int=0
,D/PMS     (  907): acquireWL(43686018): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(435870b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4343cfe0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=5 [20][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(43636de0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(43686018): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(4343cfe0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43b13190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43b13190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4716): Last usage 0, idle 1452699502s, sync interval 2592000s
I/NewsWeather( 4716): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4716): Skip sync for lookup editions
,I/NewsWeather( 4716): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4716): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4716): Unrecoverable authentication exception
E/NewsWeather( 4716): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4716): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e58e70 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 3 11 3 12
,D/PMS     (  907): acquireWL(44000978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
E/NewsWeather( 4716): Failed to syncNewsAppData
,E/NewsWeather( 4716): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(44000978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(434f6260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 161608, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(43636de0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  907): releaseWL(434f6260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): acquireWL(43af7570): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(43af7570): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(43465fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43465fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-83
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=119 entropy=108
D/wpa_supplicant( 1155): Add randomness: count=120 entropy=109
D/wpa_supplicant( 1155): Add randomness: count=121 entropy=110
D/wpa_supplicant( 1155): Add randomness: count=122 entropy=111
D/wpa_supplicant( 1155): Add randomness: count=123 entropy=112
D/wpa_supplicant( 1155): Add randomness: count=124 entropy=113
D/wpa_supplicant( 1155): Add randomness: count=125 entropy=114
D/wpa_supplicant( 1155): Add randomness: count=126 entropy=115
D/wpa_supplicant( 1155): Add randomness: count=127 entropy=116
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End prin,t parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 8: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-83
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1155): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=128 entropy=117
D/wpa_supplicant( 1155): Add randomness: count=129 entropy=118
D/wpa_supplicant( 1155): Add randomness: count=130 entropy=119
D/wpa_supplicant( 1155): Add randomness: count=131 entropy=120
D/wpa_supplicant( 1155): Add randomness: count=132 entropy=121
D/wpa_supplicant( 1155): Add randomness: count=133 entropy=122
D/wpa_supplicant( 1155): Add randomness: count=134 entropy=123
D/wpa_supplicant( 1155): Add randomness: count=135 entropy=124
D/wpa_supplicant( 1155): Add randomness: count=136 entropy=125
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS,: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (1334) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000262543433
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000262543471
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000262543481
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-83
I/wpa_supplicant( 1155): tsf=0000000262543491
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000226042147
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000262543535
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-87
I/wpa_supplicant( 1155): tsf=0000000244313858
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 262543433, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 262543471, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 262543481, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -83, frequency: 2437, timestamp: 262543491, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 226042147, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 262543535, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 244313858, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 262543460, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 262543504, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 9: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 262543524, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 10 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  74, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  7 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-83], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq:  7 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (10) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=137 entropy=126
D/wpa_supplicant( 1155): Add randomness: count=138 entropy=127
D/wpa_supplicant( 1155): Add randomness: count=139 entropy=128
D/wpa_supplicant( 1155): Add randomness: count=140 entropy=129
D/wpa_supplicant( 1155): Add randomness: count=141 entropy=130
D/wpa_supplicant( 1155): Add randomness: count=142 entropy=131
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1155): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1155): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
,D/wpa_supplicant( 1155): Add randomness: count=143 entropy=132
D/wpa_supplicant( 1155): Add randomness: count=144 entropy=133
D/wpa_supplicant( 1155): Add randomness: count=145 entropy=134
D/wpa_supplicant( 1155): Add randomness: count=146 entropy=135
D/wpa_supplicant( 1155): Add randomness: count=147 entropy=136
D/wpa_supplicant( 1155): Add randomness: count=148 entropy=137
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (1189) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000280803829
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000280803855
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78,
I/wpa_supplicant( 1155): tsf=0000000280803866
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-82
I/wpa_supplicant( 1155): tsf=0000000262543491
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000226042147
I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
,I/wpa_supplicant( 1155): level=-92
I/wpa_supplicant( 1155): tsf=0000000262543535
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000262543460
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=10
I/wpa_supplicant( 1155): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000262543504
I/wpa_supplicant( 1155): flags=[WPA
D/WirelessDisplayService(  907): getDiscoveryDongleList,
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 280803829, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 280803855, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 280803866, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -82, frequency: 2437, timestamp: 262543491, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 226042147, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  907): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 262543535, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 262543460, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 262543504, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): 8: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 280803896, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-82], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  74, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  7 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  70, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq:  7 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(434d9d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/PMS     (  907): acquireWL(434ce010): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{41d6e210: PendingIntentRecord{42454c70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=281319, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(434d9d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4348c8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(434ce010): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(4348c8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(4301f540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b7e268: PendingIntentRecord{41b7e120 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=288877, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4301f540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43015900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/PMS     (  907): releaseWL(43015900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=149 entropy=138
D/wpa_supplicant( 1155): Add randomness: count=150 entropy=139
D/wpa_supplicant( 1155): Add randomness: count=151 entropy=140
D/wpa_supplicant( 1155): Add randomness: count=152 entropy=141
D/wpa_supplicant( 1155): Add randomness: count=153 entropy=142
D/wpa_supplicant( 1155): Add randomness: count=154 entropy=143
D/wpa_supplicant( 1155): Add randomness: count=155 entropy=144
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[5] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_sup,plicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1155): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=156 entropy=145
D/wpa_supplicant( 1155): Add randomness: count=157 entropy=146
D/wpa_supplicant( 1155): Add randomness: count=158 entropy=147
D/wpa_supplicant( 1155): Add randomness: count=159 entropy=148
D/wpa_supplicant( 1155): Add randomness: count=160 entropy=149
D/wpa_supplicant( 1155): Add randomness: count=161 entropy=150
D/wpa_supplicant( 1155): Add randomness: count=162 entropy=151
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0, last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[5] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (1070) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000299043669
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
,I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000299043708
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2452
I/wpa_supplicant( 1155): level=-78
I/wpa_supplicant( 1155): tsf=0000000280803866
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-82
I/wpa_supplicant( 1155): tsf=0000000299043729
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000226042147
,I/wpa_supplicant( 1155): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-57
I/wpa_supplicant( 1155): tsf=0000000299043696
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=11
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000299043739
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=12
I/wpa_supplicant( 1155): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-89
I/wpa_supplicant( 1155): tsf=0000000299043748
I/wpa_supplicant( 1155): flag
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiP2pService(  907): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 299043669, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 299043708, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 280803866, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -82, frequency: 2437, timestamp: 299043729, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 226042147, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 299043696, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 299043739, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 7: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 299043748, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 8 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-82], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (8) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4480): --= Surplus to requirements =--
I/jxcore-log( 4480): 
I/jxcore-log( 4480): ****TEST TOOK:  ms ****
I/jxcore-log( 4480): 
,I/jxcore-log( 4480): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4480): 
,E/cutils-trace( 4833): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4833): ====startRecUseTime====
D/htc.customization.log.level( 4833):  is 
,W/CustomizationLogLevel( 4833): Level value is invalid, use default level 2
,D/CustomizationManager( 4833):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4833): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4833): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4833): Parsing tag category name = system
I/CustomizationCIDLoader( 4833): Parsing tag category name = application,
I/CustomizationCIDLoader( 4833): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4833): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4833): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4833): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4833): Parsing tag category name = Settings
D/CustomizationManager( 4833):  Read CID file spent 0.155 (s)
,D/CustomizationManager( 4833):  All configurations done spent 0.156 (s)
,W/HtcNativeFlag( 4833): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4833): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4833): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4833): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4833, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=4480
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907): Killing 4480:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
I/ActivityManager(  907):   Force finishing activity ActivityRecord{4231ab70 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  907): Copying FileAsset 0x69f6e058 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  907): channel '424ec558 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '424ec558 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '424ec558 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowManager(  907): WINDOW DIED Window{424ec558 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  907): Client connection lost with reason: 4
,W/WindowManager(  907): Failed looking up window
W/WindowManager(  907): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@4233ffc0 does not exist
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  907): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  907): WIN DEATH: null
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4480 uid 10189
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1890): Unregistering com.test.thalitest
,E/acms    ( 1890): Could not unregister removed application com.test.thalitest
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/GeofencerStateMachine( 1430): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(43c77900): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
,I/Launcher( 1268): Deferring update until onResume
,D/Launcher( 1268): waitUntilResume // bindAppsRemoved
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
D/PMS     (  907): releaseWL(43c77900): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PackageBroadcastService( 1224): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/PMS     (  907): acquireWL(441b8d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(441b8d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4848 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/ActivityManager(  907): Delaying start of: ServiceRecord{43b9ead8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/MultiDex( 4848): install
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PeopleContactsSync( 1224): CP2 sync disabled
,I/MultiDex( 4848): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1224, uid=10028, userID:0
,I/MultiDex( 4848): loading existing secondary dex files
,I/MultiDex( 4848): load found 1 secondary dex files
,I/MultiDex( 4848): install done
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4866 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PMS     (  907): acquireWL(43c41570): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,I/Icing   ( 1224): doRemovePackageData com.test.thalitest
,I/ProviderInstaller( 4848): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  907): releaseWL(43c41570): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4866): install
,I/MultiDex( 4866): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4866): loading existing secondary dex files
,I/MultiDex( 4866): load found 1 secondary dex files
,I/MultiDex( 4866): install done
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ProviderInstaller( 4866): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1417): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1417): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=4442
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  907): Killing 4442:com.android.settings:remote/1000 (adj 15): empty #17
,I/IcingCorporaProvider( 2896): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  907): Recipient 4442
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4887 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4848): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4848): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4848): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4848): 	at ctn.run(SourceFile:985)
,W/dalvikvm( 4848): threadid=12: thread exiting with uncaught exception (group=0x41680e30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4848): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4848): Process: com.google.android.gms.drive, PID: 4848
E/AndroidRuntime( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4848): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4848): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4848): 	at ctn.run(SourceFile:985)
,E/SQLiteLog( 2896): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2896): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64346988
,W/dalvikvm( 2896): threadid=16: thread exiting with uncaught exception (group=0x41680e30)
,D/Process ( 4848): killProcess, pid=4848
,D/Process ( 4848): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
,D/Process ( 2896): killProcess, pid=2896
,D/Process ( 2896): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 2896): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2896): Process: com.google.android.googlequicksearchbox:search, PID: 2896
E/AndroidRuntime( 2896): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2896): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2896): 	at cid.d(PG:186)
E/AndroidRuntime( 2896): 	at clo.g(PG:594)
E/AndroidRuntime( 2896): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2896): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2896): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2896): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2896): 	at clr.tL(PG:827)
E/AndroidRuntime( 2896): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2896): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2896): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2896): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxM,anager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,W/PackageManager(  907): Unable to load service info ResolveInfo{423e4620 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2896
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 2896): Died!
,I/ActivityManager(  907): Process com.google.android.googlequicksearchbox:search (pid 2896) has died.
I/ActivityManager(  907): Recipient 4848
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
,I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4848) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10991ms
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,E/SQLiteDatabase( 4887): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4887): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4887): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4887): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4887): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4887): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4887): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4887): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4887): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4887): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4887): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4887): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4887): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4887): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4887): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4887): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4887): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4887): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4887): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4887): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4887): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4887): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4887): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4887): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4887): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4887): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4887): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4887): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 4887): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4887): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4887): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4887): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4887): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4887): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4887): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4887): ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
,E/SQLiteOpenHelper( 4887): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4887): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4887): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4887): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4887): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4887): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4887): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4887): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4887): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4887): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4887): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4887): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4887): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4887): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4887): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4887): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4887): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4887): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4887): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4887): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4887): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4887): 	,at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4887): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4887): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4887): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4887): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4887): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4887): Opened ClientFlag.db in read-only mode
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,E/SQLiteDatabase( 4887): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4887): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4887): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4887): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4887): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4887): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4887): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4887): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4887): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4887): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4887): threadid=11: thread exiting with uncaught exception (group=0x41680e30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4887): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4887): Process: com.google.android.apps.docs, PID: 4887
E/AndroidRuntime( 4887): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4887): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4887): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4887): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4887): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4887): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4887): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4887): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4887): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/Process ( 4887): killProcess, pid=4887
,D/Process ( 4887): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4906 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  907): Recipient 4887
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=4545
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4545:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4887) has died.
,I/ActivityManager(  907): Recipient 4545
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4906): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4906): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4906): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4906): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4906): threadid=10: thread exiting with uncaught exception (group=0x41680e30)
,E/ActivityManager(  907): App crashed! Process: com.android.keychain
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4919 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4906): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4906): Process: com.android.keychain, PID: 4906
E/AndroidRuntime( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4906): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4906): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4906): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4906): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4906): killProcess, pid=4906
,D/Process ( 4906): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452699563918.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  907): Recipient 4906
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.android.keychain (pid 4906) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10702ms
,D/AppTag  ( 4919): getInstance(Context context)
,D/AppTag  ( 4919): getInstance(Context context)
,D/AppTag  ( 4919): onCreate()
,D/PMS     (  907): acquireWL(43c02c10): PARTIAL_WAKE_LOCK  AsyncService 0x1 4201 10160 null
,D/PMS     (  907): releaseWL(43c02c10): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4937 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  907): acquireWL(4320f638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41d6e210: PendingIntentRecord{42454c70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=312882, Int=0
,I/DeviceManagement( 4937): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4937 dbg=false s=true
,I/DeviceManagement( 4937): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4937): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4937): WorkflowService: Starting workflow service
I/DeviceManagement( 4937): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ae6380] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4937): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4937): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4937): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4937): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4951 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4937): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4937): SessionStateController: Checking invariants...
,D/Documents( 4951): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4951): Loading roots for com.android.externalstorage.documents
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@41b43d70 +
,I/Prism.WidgetManager( 1268): onLoadItems() +
,E/SQLiteDatabase( 4951): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4951): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4951): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4951): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4951): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4951): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4951): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4951): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4951): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4951): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4951): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4951): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4951): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4951): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4951): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4951): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4951): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4951): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4951): threadid=1: thread exiting with uncaught exception (group=0x41680e30)
E/AndroidRuntime( 4951): FATAL EXCEPTION: main
E/AndroidRuntime( 4951): Process: com.android.documentsui, PID: 4951
E/AndroidRuntime( 4951): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4951): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4951): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4951): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4951): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4951): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4951): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4951): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4951): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4951): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4951): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4951): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4951): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4951): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4951): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4951): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4951): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4951): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4951): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4951): 	... 10 more
,I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4965 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  907): killProcessQuiet, pid=3943
,I/ActivityManager(  907): Killing 3943:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  907): App crashed! Process: com.android.documentsui
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/Process (  907): killProcessQuiet, pid=4580
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  907): Killing 4580:com.google.android.setupwizard/u0a78 (adj 15): empty #17
I/ActivityManager(  907): Recipient 4580
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452699564231.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process ( 4951): killProcess, pid=4951
D/Process ( 4951): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Recipient 4951
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Process com.android.documentsui (pid 4951) has died.
D/ExternalStorage( 4965): After updating volumes, found 1 active roots
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,E/SQLiteDatabase( 4937): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4937): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4937): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4937): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4937): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4937): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4937): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4937): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4937): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4937): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4937): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4937): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4937): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4937): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4937): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4937): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4937): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4937): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  907): Resuming delayed broadcast
I/DeviceManagement( 4937): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4937): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4937): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4981 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4937): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4937): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4937): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4937): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4937): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4937): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4937): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4937): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4937): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4937): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4937): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ae6380]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4937): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4937): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4937): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4937): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4937): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4937): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4937): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4937): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4937): WorkflowService: Stopping workflow service
,I/ActivityManager(  907): Recipient 3943
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 3943): Died!
,E/SQLiteDatabase( 4981): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4981): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4981): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4981): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4981): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4981): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4981): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4981): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4981): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4981): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4981): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4981): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4981): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4981): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4981): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4981): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4981): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4981): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4981): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4981): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4981): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4981): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4981): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4981): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4981): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4981): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4981): Opened MyDB.db in read-only mode
,D/Process (  907): killProcessQuiet, pid=4596
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4596:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4596
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,D/PMS     (  907): acquireWL(440a3420): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(4320f638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b10c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(440a3420): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(43b10c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null

```
