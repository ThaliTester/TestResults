#### Test 56151093b6ab50f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  911): mEventCount = 1200
,E/cutils-trace( 4425): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4425): ====startRecUseTime====
D/htc.customization.log.level( 4425):  is 
W/CustomizationLogLevel( 4425): Level value is invalid, use default level 2
D/CustomizationManager( 4425):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4425): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4425): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4425): Parsing tag category name = system
I/CustomizationCIDLoader( 4425): Parsing tag category name = application
I/CustomizationCIDLoader( 4425): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4425): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4425): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4425): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4425): Parsing tag category name = Settings
D/CustomizationManager( 4425):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4425):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 4425): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4425): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4425): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4425): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4425
D/PMS     (  911): acquireHCC(42443f98): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(420d87f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
W/asset   (  911): Copying FileAsset 0x667afe88 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1112189928
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cd4be0
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  911): acquireWL(42f26218): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/ActivityManager(  911): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4436 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4436): Copying FileAsset 0x5c8a6428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4436): Binding Chromium to main looper Looper (main, tid 1) {41b6e120}
I/LibraryLoader( 4436): Expected native library version number "",actual native library version number ""
I/chromium( 4436): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4436): Initializing chromium process, renderers=0
D/PMS     (  911): acquireWL(423386e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): acquireWL(43cf8a68): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427a6ac0:true
D/PMS     (  911): releaseWL(423386e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4436): 1102593096: getState(). Returning 12
I/Adreno-EGL( 4436): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4436): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4436): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4436): Local Branch: 
I/Adreno-EGL( 4436): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4436): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4436):                  aa63bbd948f41d15fc72f585e
W/chromium( 4436): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4436): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4436): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4436): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4436): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4436): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4436): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4436): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4436): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4436): CordovaWebView is running on device made by: HTC
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/AwContents( 4436): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  911): Disable input method client, pid=1273
,W/ResourceType( 4436): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4436): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bb52f8, mServedView=org.apache.cordova.engine.SystemWebView{41b7af60 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  911): Enable input method client, pid=4436
W/AwContents( 4436): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  911): Displayed com.test.thalitest/.MainActivity: +295ms
D/PMS     (  911): releaseWL(42f26218): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1139): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/JsMessageQueue( 4436): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4436): JniHelper::setJavaVM(0x4163d048), pthread_self() = 1663524672
,D/JX-Cordova( 4436): jxcore cordova android initializing
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 12.043MB for 63974-byte allocation
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 12.087MB for 95956-byte allocation
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 12.157MB for 143930-byte allocation
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 12.271MB for 215890-byte allocation
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 12.447MB for 323830-byte allocation
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 13.122MB for 728606-byte allocation
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 13.719MB for 1092904-byte allocation
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 14.638MB for 1639352-byte allocation
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 15.882MB for 2459024-byte allocation
,I/dalvikvm-heap( 4436): Grow heap (frag case) to 18.072MB for 3688532-byte allocation
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
,D/PMS     (  911): releaseHCC(42443f98): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  911): releaseHCC(420d87f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4436): Initializing JXcore engine
,W/jxcore-log( 4436): JXcore engine is ready
,W/jxcore-log( 4436): Starting JXcore engine
,W/jxcore-log( 4436): Platform android
W/jxcore-log( 4436): 
,W/jxcore-log( 4436): Process ARCH arm
W/jxcore-log( 4436): 
,I/jxcore-log( 4436): JXcore Cordova bridge is ready!
I/jxcore-log( 4436): 
,W/jxcore-log( 4436): JXcore engine is started
,I/chromium( 4436): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4436): Toggling radios to true
I/jxcore-log( 4436): 
,D/BluetoothAdapter( 4436): enable(): BT is already enabled..!
,D/WifiManager( 4436): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  911): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  911): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  911): Settings:Agentvalue: 2
W/Settings:Agent(  911): >> traceCallingStack()
W/Settings:Agent(  911): Process.myPid(): 911
W/Settings:Agent(  911): Process.myTid(): 1278
W/Settings:Agent(  911): Process.myUid(): 1000
W/Settings:Agent(  911): 
W/Settings:Agent(  911): 
W/System.err(  911): java.lang.Throwable: stack dump
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
,W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  911): 
W/Settings:Agent(  911): << traceCallingStack(): 1(ms)
,D/WifiManager( 4436): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiNative-wlan0(  911): doBoolean: DISCONNECT
,D/WifiManager( 4436): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1139): TDLS: Tear down peers
,I/wpa_supplicant( 1139): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4436): Radios toggled
I/jxcore-log( 4436): 
D/WifiService(  911): setWifiEnabled: true pid=4436, uid=10389
E/WifiService(  911): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  911): New client listening to asynchronous messages
I/WifiService(  911): isSprintWifiRestricted(): false
I/WifiService(  911): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  911): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4436): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4436): 
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1139): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1139): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1139): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  911): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  911): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1139): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  911): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  911): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1139): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1139): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1139): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1139): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb808dbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1139):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1139): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1139): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1139): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1139): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1139): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1139): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1139): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1139): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1139): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1139): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1139): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1139): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1139): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1139): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1139): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1139): send_and_recv erro,r 0 - cmd 18
D/wpa_supplicant( 1139): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1139): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1139): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1139): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1139): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1139): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1139): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1139): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1139): nl80211: Event message available
D/wpa_supplicant( 1139): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1139): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  911): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  911): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  911):    returned true
D/WifiPerfLock(  911): release()
D/WifiStateMachine(  911): PerfLock released for exiting ConnectedState
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
,D/Tethering(  911): interfaceStatusChanged wlan0, false
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1139): Power_Mode_Type mode = 0
I/wpa_supplicant( 1139): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1139): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/Tethering(  911): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  911):    returned true
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  911): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  911): acquireWL(425d7c58): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 911 1000 null
D/WifiP2pService(  911): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  911): [RunningState] Stop DHCP
D/WifiNative-wlan0(  911): doBoolean: RECONNECT
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1139): Fast associate: Old scan results
I/wpa_supplicant( 1139): wpa_supplicant_scan enter
I/wpa_supplicant( 1139): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1139): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1139): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  911):    returned true
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  911): Enter handleNetworkDisconnect
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1139): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1139): nl80211: Event message available
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
,D/wpa_supplicant( 1139): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20776 mDataStallAlarmIntent=PendingIntent{41fc03d0: PendingIntentRecord{42488618 android broadcastIntent}}
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1139): Power_Mode_Type mode = 0
I/wpa_supplicant( 1139): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  911): isAvailable+-
D/UsbnetStateTracker(  911): reconnect
D/UsbnetStateTracker(  911): isAvailable+-
D/WifiNative-wlan0(  911):    returned true
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  911): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  911): default: reconnect()
D/MDST    (  911): default: setTeardownRequested(false)
D/MDST    (  911): default: setEnableApn apnType =default , enable=true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1139): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  911):    returned true
D/WifiP2pService(  911): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  911): Exit handleNetworkDisconnect
D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  911): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  911): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 4058): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 4058): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  911): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/PMS     (  911): releaseWL(43cf8a68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/WifiService(  911): New client listening to asynchronous messages
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): handleConnectivityChange: resetting
,D/ConnectivityService(  911): resetConnections(wlan0, 3)
D/WISPrService( 4058): >>>>>WISPrService start isConnected = false<<<<<
V/NativeCrypto( 1372): Read error: ssl=0x666ad400: I/O error during system call, Connection timed out
,D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4058): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] entry_id:3   entry:0xb8d8e590  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8d89c20  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8d8e2b8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8d92f70  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8d92e40  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8d8e458  removed 
V/NativeCrypto( 1372): SSL shutdown failed: ssl=0x666ad400: I/O error during system call, Broken pipe
D/libc    (  363): [NET] entry_id:7   entry:0xb8d8e390  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/PMS     (  911): acquireWL(423f0bd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  911): startScan Pid: 911 Uid 1000
D/WifiNative-wlan0(  911): doBoolean: SCAN
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1139): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  911):    returned false
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
D/PMS     (  911): acquireWL(426de558): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  911): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): reportInetCondition for net -1, percentage: 0 by  (1372/10029)
,D/BatSI   (  911): WIFI scan started for: 650a0300 uid:1000
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  911): releaseWL(423f0bd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  911): mActiveDefaultNetwork: -1
,D/ConnectivityService(  911): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  911): releaseWL(426de558): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  911): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  911): bSetPropertyMultiRAB:false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/PMS     (  911): acquireWL(42659460): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4283/10100)
,D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  911): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  911): ipv4Default null
,I/Tethering(  911): No IPv4 upstream interface, giving up.
,D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
D/CaptivePortalTracker(  911): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  911): NoActiveNetworkState
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4283/10100)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1600/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (3859/10154)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/NetworkMonitor( 3859): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2374/10021)
,D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  911): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  911): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4487 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/PMS     (  911): releaseWL(42659460): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4487): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4487): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4487): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4487): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4487): Preparing secondary program dexes.
V/DexLibLoader( 4487): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4487): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4487): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4487): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4487): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4487): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4487): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4487): Dex already copied
D/OdexVerifier( 4487): Odex verification is skipped.
,V/DexLibLoader( 4487): Creating class loader
,V/DexLibLoader( 4487): Finished creating class loader
V/DexLibLoader( 4487): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4487): Dex already copied,
D/OdexVerifier( 4487): Odex verification is skipped.
,V/DexLibLoader( 4487): Creating class loader
,V/DexLibLoader( 4487): Finished creating class loader
V/DexLibLoader( 4487): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4487): Dex already copied
D/OdexVerifier( 4487): Odex verification is skipped.
,V/DexLibLoader( 4487): Creating class loader,
V/DexLibLoader( 4487): Finished creating class loader
V/DexLibLoader( 4487): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar,
V/DexLibLoader( 4487): Dex already copied
D/OdexVerifier( 4487): Odex verification is skipped.
,V/DexLibLoader( 4487): Creating class loader
V/DexLibLoader( 4487): Finished creating class loader
V/DexLibLoader( 4487): Verifying classes from secondary dexes.
D/DexLibLoader( 4487): DexLibLoader.ensureDexLoaded took 16 ms
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42241730
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42241730, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fba8e0
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@42292dc8
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,W/PMS     (  911): mWirelessDisplayManager is null
,D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/dalvikvm( 4487): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1139): nl80211: Event message available
D/wpa_supplicant( 1139): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1139): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1139): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1139): nl80211: Survey data missing
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1139): Sorted scan results
I/wpa_supplicant( 1139): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1139): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1139): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1139): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1139): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1139): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1139): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1139): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1139): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1139): wpa_supplicant_pick_network+
I/wpa_supplicant( 1139): Selecting BSS from priority group 1
I/wpa_supplicant( 1139): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1139): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1139): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1139): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1139):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1139):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1139): Start print parameters
I/wpa_supplicant( 1139): wpa_s->wpa_state is 3
I/wpa_supplicant( 1139): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1139): isConcurrentMode() is 0
I/wpa_supplicant( 1139): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1139): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1139): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1139): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1139): wpa_s->reassociate is 1
I/wpa_supplicant( 1139): wpa_s->is_screen_on 1
I/wpa_supplicant( 1139): wpa_s->ifname wlan0
I/wpa_supplicant( 1139): End print parameters
I/wpa_supplicant( 1139): selected network = 1
D/wpa_supplicant( 1139): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb808f4e8  current_ssid=0x0
D/wpa_supplicant( 1139): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1139): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1139): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1139): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1139): check if in concurrent case
,I/wpa_supplicant( 1139): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
D/wpa_supplicant( 1139): wpa_supplicant_associate, 1777
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1139): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1139): wpa_supplicant_associate, 1795,
D/wpa_supplicant( 1139): RSN: PMKSA cache search - network_ctx=0xb808f4e8 try_opportunistic=0
D/wpa_supplicant( 1139): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1139): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1139): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1139): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1139): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1139): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1139): nl80211: Unsubscribe mgmt frames handle 0xb808e718 (mode change)
D/wpa_supplicant( 1139): nl80211: Subscribe to mgmt frames with non-AP handle 0xb808e718
D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718,
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718,
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1139): nl80211: Register frame type=0xd0 nl_handle=0xb808e718
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1139): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1139):   * bssid=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 1139):   * freq=2412
D/wpa_supplicant( 1139):   * Auth Type 0
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1139):   * WPA Versions 0x2
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1139): nl80211: Connect request send successfully,
D/wpa_supplicant( 1139): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1139): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1139): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1139): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1139): reply (351) for get BSS: id=0
I/wpa_supplicant( 1139): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1139): freq=5220
I/wpa_supplicant( 1139): level=-47
I/wpa_supplicant( 1139): tsf=0000000107371384
I/wpa_supplicant( 1139): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1139): ssid=NG7005g
I/wpa_supplicant( 1139): ====
I/wpa_supplicant( 1139): id=1
I/wpa_supplicant( 1139): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1139): freq=2412
I/wpa_supplicant( 1139): level=-58
I/wpa_supplicant( 1139): tsf=0000000107371397
I/wpa_supplicant( 1139): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1139): ssid=NG700
I/wpa_supplicant( 1139): ====
I/wpa_supplicant( 1139): id=2
I/wpa_supplicant( 1139): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1139): freq=2412
I/wpa_supplicant( 1139): level=-59
I/wpa_supplicant( 1139): tsf=0000000107371401
I/wpa_supplicant( 1139): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1139): ssid=01ABC
I/wpa_supplicant( 1139): ####
,D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 107371384, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 107371397, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 107371401, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
D/BatSI   (  911): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 315ms
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43c62910)
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
D/PMS     (  911): OOBE c monitor 11
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
D/PMN     (  911): wakingUp
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
D/NfcService( 1258): ScreenObserver: OFF
D/NfcService( 1258): applyRouting - 0
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1258): applyRouting -2
I/WindowManager(  911): No lock screen! windowToken=null
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
D/PMN     (  911): onScreenOn
I/InputMethodManagerService(  911): Disable input method client, pid=4436
D/PMS     (  911): acquireWL(443660f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  911): releaseWL(443660f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  911): doBoolean: SET pno 0
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0,
I/wpa_supplicant( 1139): SET_SCREEN_ON:On
I/wpa_supplicant( 1139): htc_wext_set_keepalive +
,I/wpa_supplicant( 1139): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1139): getPrivFuncNum +	
I/wpa_supplicant( 1139): getPrivFuncNum -, cmd = 0x8bf6,
I/wpa_supplicant( 1139): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1139): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1139): htc_wext_set_TX_TRACKING (0)+,
I/wpa_supplicant( 1139): htc_wext_set_TX_TRACKING - ret = 0,
D/WifiNative-wlan0(  911):    returned true
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1139): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  911):    returned true,
D/PMS     (  911): acquireWL(43960840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/AlarmManager(  911): ACTION_SCREEN_ON,
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  911): releaseWL(43960840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/MtpService( 2374): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1258): applyRouting - 0
,D/MtpService( 2374): [MTP][onReceive]-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,D/NfcService( 1258): applyRouting -2
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  911): acquireWL(437f67d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  911): releaseWL(437f67d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  911): updateScreenOn: false
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1139): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1139): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1139): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1139): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1139): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1139): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1139): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1139): nl80211: Event message available
D/wpa_supplicant( 1139): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1139): nl80211: Connect event
D/wpa_supplicant( 1139): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1139): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1139): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1139): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1139): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1139): Add randomness: count=8 entropy=3
I/wpa_supplicant( 1139): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1139): TDLS: Remove peers on association
D/wpa_supplicant( 1139): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1139): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1139): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1139): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1139): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1139): EAPOL: enable timer tick
D/wpa_supplicant( 1139): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1139): htc_wext_set_keepalive +
I/wpa_supplicant( 1139): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1139): getPrivFuncNum +	
D/WifiMonitor(  911): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1139): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1139): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  911): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1139): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1139): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1139): Get randomness: len=32 entropy=4
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  911): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  911): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  911): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  911): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantSta,teChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  911): Enter handleAssociatedWithEvent
D/WifiStateMachine(  911): Associated
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/WifiStateMachine(  911): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  911): Exit handleAssociatedWithEvent
D/WifiStateMachine(  911): BSSID was changed, update WiFi database
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
D/Tethering(  911): interfaceStatusChanged wlan0, true
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  911): This record is existed, only update it...
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
I/wpa_supplicant( 1139): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb808e9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1139):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1139): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1139): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fa4b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1139):    broadcast key
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1139): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1139): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1139): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1139): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1139): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1139): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  911): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1139): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1139): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1139): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1139): set send_ind_to_ndc = 0
I/wpa_supplicant( 1139): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1139): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1139): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1139): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1139): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1139): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1139): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1139): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1139): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1139): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1139): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1139): EAPOL authentication completed successfully
I/wpa_supplicant( 1139): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1139): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1139): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1139): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
D/Tethering(  911): interfaceStatusChanged wlan0, true
D/Tethering(  911): [isWifi] getHotspotEnabled: false
I/ClockThread( 1117): stop update clock
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/dalvikvm( 4487): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  911): fetchFrequency(), freq = 2412
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/PMS     (  911): acquireWL(44313210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(44313210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(43929508): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  911): This record is existed, only update it...
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/PMS     (  911): releaseWL(43929508): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WISPrService( 4058): >>>>>WISPrService start isConnected = false<<<<<
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOn: 1453102516517
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOn: 1453102516517
D/WISPrService( 4058): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): mActiveDefaultNetwork: -1
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fba8e0
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fba8e0, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@42292dc8
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DhcpStateMachine(  911): [StoppedState] Start DHCP
D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
D/PMN     (  911): goingToSleep
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,D/PMS     (  911): acquireWL(43960ee8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1139): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20777 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1139): SET_SCREEN_ON:Off
I/wpa_supplicant( 1139): htc_wext_set_keepalive +
I/wpa_supplicant( 1139): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1139): getPrivFuncNum +	
I/wpa_supplicant( 1139): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1139): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1139): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1139): get_ip_address source addr = 02000000
I/wpa_supplicant( 1139): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1139): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1139): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1139): Power_Mode_Type mode = 1
I/wpa_supplicant( 1139): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
I/AlarmManager(  911): [AlarmQueuing] wifi connection: true
D/PMS     (  911): acquireWL(425eaee0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/WifiStateMachine(  911): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  911): acquireWL(43f93cf0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 911 1000 null
,D/WifiStateMachine(  911): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  911):    returned null
E/WifiStateMachine(  911): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/SRS_Proc(  371): ParamSet string: screen_state=off
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  911):    returned null
,D/ContactMessageStore( 1243): start background delete task...
D/WifiP2pService(  911): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41d3ac60 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  911): releaseWL(425eaee0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41d3ac60 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkPolicy(  911): updateScreenOn: false
D/ContactMessageStore( 1243): size: 0 , 0
D/ContactMessageStore( 1243): Background delete complete
,E/FbInjectorInitializer( 4487): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,D/AutoSetting( 1332): service - mHandler: cancel location update
,D/AutoSetting( 1332): service -           changes count: 0
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] getTotalRam: 1873 Mb
D/PMS     (  911): acquireWL(426f4e38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(426f4e38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(42717750): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42717750): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOff
,W/fb4a(:<default>):StaticBindingVerifier( 4487): Verify
,D/WifiService(  911): New client listening to asynchronous messages
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4487): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4487): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  911): killProcessQuiet, pid=4214
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 4214:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4214
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  911): Client connection lost with reason: 4
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  911): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4522 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/AutoSetting( 1332): Util - no network available!
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1332): service - mHandler: cancel location update
,D/AutoSetting( 1332): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4487): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4487): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/ActivityManager(  911): Activity pause timeout for ActivityRecord{42451e08 u0 com.test.thalitest/.MainActivity t2}
,W/fb4a(:<default>):UserScope( 4487): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4522): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4522): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4522): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4522): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  911): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4536 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=3839
,I/ActivityManager(  911): Killing 3839:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4522/10079)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4522/10079)
I/ActivityManager(  911): Recipient 3839
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4522/10079)
,I/ActivityManager(  911): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4550 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=4118
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 4118:com.google.android.talk/u0a111 (adj 15): empty #17
,E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4487): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4487): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4487): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4487): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4487): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4487): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4487): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 9.967MB for 84664-byte allocation
W/dalvikvm( 4487): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4487): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4487): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4487): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4487): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4487): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 9.993MB for 39954-byte allocation
,W/GAV2    ( 4550): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 10.069MB for 79892-byte allocation
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 4118
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 10.096MB for 28144-byte allocation
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4550/10151)
,V/WebViewChromiumFactoryProvider( 4550): Binding Chromium to main looper Looper (main, tid 1) {41b67248}
,I/LibraryLoader( 4550): Expected native library version number "",actual native library version number ""
,I/chromium( 4550): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4550): Initializing chromium process, renderers=0
,D/PMS     (  911): acquireWL(42f26020): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  911): acquireWL(432586a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4550): BLUETOOTH permission is missing!
D/PMS     (  911): releaseWL(42f26020): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4550): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4550): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4550): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4550): Local Branch: 
I/Adreno-EGL( 4550): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4550): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4550):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 10.283MB for 75760-byte allocation
,I/NSApplication( 4550): Starting up...
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4325e0c8 u0 ReceiverList{4325dfa8 4487 com.facebook.katana/10027/u0 remote:43d58648}}
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4325e0c8 u0 ReceiverList{4325dfa8 4487 com.facebook.katana/10027/u0 remote:43d58648}}
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4550/10151)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4550/10151)
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{442620c8 u0 ReceiverList{44262068 4487 com.facebook.katana/10027/u0 remote:44261ba8}}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4034/10160)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4034/10160)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
D/Process (  911): killProcessQuiet, pid=4253
D/wpa_supplicant( 1139): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1139): EAPOL: disable timer tick
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 4253:com.google.android.partnersetup/u0a32 (adj 15): empty #17
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,I/iu.Environment( 2184): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2184): num queued entries: 0
I/iu.UploadsManager( 2184): num updated entries: 0
,I/iu.SyncManager( 2184): NEXT; no task
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
I/ActivityManager(  911): Recipient 4253
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4589 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  911): acquireWL(4279e438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4279e438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 4436): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4436): 
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4487): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4487): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4589): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4487): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/SmartSyncUtils( 4589): isEpsOn(), nState = 0
D/PMS     (  911): acquireWL(443978c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4589 1000 null
,D/SmartSyncUtils( 4589): getMobilePolicyEnabled, result = true
D/PMS     (  911): releaseWL(443978c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  911): Killing 4283:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/Process (  911): killProcessQuiet, pid=4283
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1332): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  911): Recipient 4283
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TetherSettings( 4058): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4058): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4058): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4058): Cust_ConnectToPC   : spcsc>false
D/        ( 4058): Cust_ConnectToPC   : IPT>true
,D/        ( 4058): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4058): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4058): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4058): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4058): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4058): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4058): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4058): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4058):  defaultType:0
W/ContextImpl( 4058): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4589): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4589): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4589): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4589): isEpsOn(), nState = 0
D/WifiService(  911): New client listening to asynchronous messages
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42292dc8
,W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42292dc8, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42292dc8, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42292dc8
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42556fc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42556fc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/jxcore-log( 4436): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4436): 
,I/jxcore-log( 4436): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4436): 
,I/jxcore-log( 4436): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4436): 
,I/jxcore-log( 4436): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4436): 
,I/jxcore-log( 4436): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4436): 
,I/jxcore-log( 4436): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4436): 
,I/jxcore-log( 4436): Test app app.js loaded
I/jxcore-log( 4436): 
,I/Choreographer( 4436): Skipped 264 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4436): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4436): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4436): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b7af60 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  911): releaseWL(43960ee8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  911): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1139): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1139): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1139): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1139): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  911): releaseWL(43f93cf0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [2][0][0]
I/wpa_supplicant( 1139): Change stage from stage0 to stage3
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1139): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  911): gateway: /192.168.1.1
,D/WifiNative-wlan0(  911): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1139): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1139): htc_wext_set_keepalive +
I/wpa_supplicant( 1139): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1139): getPrivFuncNum +	
I/wpa_supplicant( 1139): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1139): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1139): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1139): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1139): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent L2ConnectedState
,D/WifiStateMachine(  911): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  911): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  911): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  911): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  911): WAN detection
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  911): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  911): default: teardown()
D/MDST    (  911): default: setTeardownRequested(true)
D/MDST    (  911): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  911): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  911): default: setTeardownRequested(true)
D/ConnectivityService(  911): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4058): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/ConnectivityService(  911): Unexpected mtu value: android.net.wifi.WifiStateTracker@424ee1a8
,D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  911): syncGetConfiguredNetworks
D/ConnectivityService(  911): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  911): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  911): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  911): handleConnectivityChange: resetting
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WirelessDisplayService(  911): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  911):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  911): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  911): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  911): acquireWL(43012c50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4522/10079)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:3
D/PMS     (  911): acquireWL(42338280): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1453102465640 min interval config: 0 actual interval: 53261
D/PMS     (  911): acquireWL(41f3c900): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42338280): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checking schedule, now: 1453102518909 next: 1453102495614
,I/CheckinService( 2184): active receiver: enabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2184): Preparing to send checkin request
,I/EventLogService( 2184): Accumulating logs since 1453102461635
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  911): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [1][0][0]
D/PMS     (  911): releaseWL(43012c50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  911): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4647 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4647): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4647): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4647): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4647): install
,I/MultiDex( 4647): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4647): loading existing secondary dex files
,I/MultiDex( 4647): load found 3 secondary dex files
,I/MultiDex( 4647): install done
,W/dalvikvm( 4647): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4647): VFY: unable to resolve instance field 36
,W/dalvikvm( 4647): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4647): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/dalvikvm( 4436): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4436): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4436): BLE advertisement is supported
I/jxcore-log( 4436): 
,I/ProviderInstaller( 4647): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4647): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4647): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4647): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4647): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4647): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4647): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4647): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/WearableService( 1226): callingUid 10029, callindPid: 1226
,D/LocationInitializer( 2184): Restart initialization of location
,E/MDM     ( 1226): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1226): No location to return for getLastLocation()
,W/FusedLocationProvider( 1226): location=null
D/PMS     (  911): acquireWL(4279a3b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(4279a3b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
D/AuthorizationBluetoothService( 1372): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1372): Proximity feature is not enabled.
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4647): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=4224010264
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,W/fb4a(:<default>):UserScope( 4487): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4487): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,D/PMS     (  911): releaseWL(425d7c58): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  911): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  911): bSetPropertyMultiRAB:false
D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  911): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/Tethering(  911): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
I/Tethering(  911): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
I/Tethering(  911): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  911): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  911): Found interface wlan0
,D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
I/NetworkMonitor( 3859): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [2][0][0]
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/PMS     (  911): acquireWL(426f0c38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(426f0c38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4522/10079)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (3859/10154)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1600/10029)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.musicenhancer (3882/10053)
D/CaptivePortalTracker(  911): NoActiveNetworkState
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(430ffed0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1600/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
D/PMS     (  911): releaseWL(430ffed0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  911): It's IPV6 link-local unicast address, No need to broadcast it!
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(4438c898): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
D/PMS     (  911): releaseWL(4438c898): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4487): Called registerBroadcastReceiver twice.
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2374/10021)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4522): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4522): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1332): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4550/10151)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
D/AutoSetting( 1332): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1332): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4034/10160)
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4034/10160)
,D/PMS     (  911): acquireWL(4268e278): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1453102465640 min interval config: 0 actual interval: 54342
D/PMS     (  911): releaseWL(4268e278): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4034): Grow heap (frag case) to 13.525MB for 1821008-byte allocation
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2184): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2184): num queued entries: 0
,I/iu.UploadsManager( 2184): num updated entries: 0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,I/iu.SyncManager( 2184): NEXT; no task
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
,D/libc    ( 1372): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6f5c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/PMS     (  911): acquireWL(44399160): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4487/10027)
,I/Adreno-EGL( 4647): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4647): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4647): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4647): Local Branch: 
I/Adreno-EGL( 4647): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4647): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4647):                  aa63bbd948f41d15fc72f585e
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 253
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (4647/10029)
,I/Adreno-EGL( 4647): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4647): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4647): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4647): Local Branch: 
I/Adreno-EGL( 4647): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4647): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4647):                  aa63bbd948f41d15fc72f585e,
,D/PMS     (  911): acquireWL(426b90c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  911): releaseWL(44399160): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,I/Adreno-EGL( 4647): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4647): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4647): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4647): Local Branch: 
I/Adreno-EGL( 4647): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4647): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4647):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
D/PMS     (  911): releaseWL(426b90c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(43664958): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
D/PMS     (  911): releaseWL(43664958): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(432586a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3332324328
,I/WVCdm   (  371): CdmEngine::CloseSession
,W/Settings( 4647): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =db29 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2184): Sending checkin request (12078 bytes)
,D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=18 [22][4][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [1][0][0]
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=20 [5][1][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,I/CheckinTask( 2184): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2184): Checking schedule, now: 1453102521340 next: 1453625458335
,I/CheckinService( 2184): active receiver: disabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,I/CheckinService( 2184): Checking schedule, now: 1453102521366 next: 1453625458335
,I/CheckinService( 2184): active receiver: disabled
,D/CheckinService( 2184): Recording last checkin time for package unspecified as 1453102521371
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,D/PMS     (  911): releaseWL(41f3c900): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/AutoSetting( 1539): service - handleMessage() stop self
,D/AutoSetting( 1539): service - onDestroy() END
,D/AutoSetting( 1539): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4306
,I/ActivityManager(  911): Killing 4306:com.htc.backup/1000 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 4306
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =38e1 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  911): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4550): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  911): killProcessQuiet, pid=4324
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4324:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4324
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  911): killProcessQuiet, pid=3882
,I/ActivityManager(  911): Killing 3882:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 3882
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1332): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1332): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1332): service - requestNLP() NetworkLocationProvider not enabled
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  911): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4696 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsUpdated
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4696): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4696): MmsConfig.loadMmsSettings
,W/dalvikvm( 4696): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4696): VFY: unable to resolve instance field 36
,W/dalvikvm( 4696): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4696): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4696, uid=10111, userID:0
,W/Settings( 4696): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  911): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4720 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4696, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4696, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4696, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4696, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4696, uid=10111, userID:0
,D/PMS     (  911): acquireWL(4387f008): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4696 10111 null
,I/[PluginManager]RegisterService( 1332): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1332): handle notify Blinkfeed plugin client changed
,D/MessageFrequencyProvider( 4720): onCreate
,I/IcingCorporaProvider( 2853): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,V/GetPrviateResource( 4720): GetPrviateResource
,V/GetPrviateResource( 4720): GetPrviateResource
,D/MmsCustomizationProvider( 4720): query uri: content://htc-mms-customization/mms-ua/ua_string
I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  911): acquireWL(4272b6d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4034 10160 null
D/PMS     (  911): acquireWL(431141d0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4034): Grow heap (frag case) to 15.225MB for 1821008-byte allocation
,I/ProviderInstaller( 4696): Installed default security provider GmsCore_OpenSSL
,D/MmsCustomizationProvider( 4720): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/MessageCustFlag( 4720): sense_version=6.0
,D/BTAccessoryUtil( 4720): createReceiver
D/PMS     (  911): releaseWL(4272b6d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  911): releaseWL(4387f008): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  911): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/PackageManager(  911): Unable to load service info ResolveInfo{42713f00 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/BTAccessoryUtil( 4720): registerReceiver return intent = null
,D/MessageCustFlag( 4720): sku_id=99
,W/SystemReader( 4720): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  911): Resuming delayed broadcast
,I/Babel   ( 4696): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4696): MmsConfig.loadFromDatabase
I/dalvikvm-heap( 4034): Grow heap (frag case) to 16.956MB for 1821008-byte allocation
,D/Messaging( 4720): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4720): networkCode: 
,D/MessageCustFlag( 4720): sku_id=99
D/MmsConfig( 4720): SIE smsPri: null
,D/MmsConfig( 4720): networkCode: 
,E/Babel   ( 4696): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4696): MmsConfig.loadFromResources
,E/Babel   ( 4696): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4696): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/HtcTelephonyCapability( 4720): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4720): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4720): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4720): Cannot find qct_8960_interface, use default value instead
,D/Process (  911): killProcessQuiet, pid=4270
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 4270:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4270
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2184): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2184): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  911): start
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bfacb0 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/IcingCorporaProvider( 2853): UpdateCorporaTask done [took 960 ms] updated apps [took 960 ms] 
,D/LocationProviderProxy(  911): applying state to connected service
D/PMS     (  911): acquireWL(426c0268): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(426c0268): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  911): applying state to connected service
,D/PMS     (  911): acquireWL(425a5a30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(425a5a30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(424b8aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(424b8aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4248c7e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4248c7e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bfacb0 -
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  911): releaseWL(431141d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4720): mNeedToUpdateDate2 start
,D/MmsConfig( 4720): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4720): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4720): 
D/MmsAsyncWorkHandler( 4720): HM tk = 20001
D/ReportIndicatorCache( 4720): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4720): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b746a8
,I/Messaging( 4720): mccmnc> 
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/DraftCache( 4720): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4720): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsConfig( 4720): networkCode: 
,D/Messaging( 4720): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4720): mNeedToUpdateDate2: false
,D/MessageCustFlag( 4720): sense_version=6.0
,D/Jerry   ( 4720): start to preload cursor >>>>>>>
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/PhoneStorageUtil( 4720): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4720): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4720): createReceiver
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/TelephUtils( 1243): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,V/MmsProvider( 1243): Update uri=content://mms, match=0
,V/MmsProvider( 1243): selection=st=129 AND m_type!=134
D/Messaging( 4720): ViewCache CreatePreload
D/Messaging( 4720): Reset downloading state: 0
,D/Messaging( 4720): ViewCache CreatePreloadOnlyMultipleOpsList
,V/MmsSystemEventReceiver( 4720): TransactionService is going to be woken up.
,D/Cust_MMSMS( 4720): _has_set_default_values_2=true
,V/TransactionService( 4720): 1-Creating TransactionService
D/MsgPreferenceUtils( 4720): def_index: 0
,V/TransactionService( 4720): onStartCommand: 1
,D/MmsSystemEventReceiver( 4720): unRegisterForConnectionStateChanges
,D/MsgPreferenceUtils( 4720): globalIndex = 1
V/TransactionService( 4720): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4720): Loading previous transactions.
D/MsgPreferenceUtils( 4720): phone state: true
D/MsgPreferenceUtils( 4720): sd state: false
,D/MsgPreferenceUtils( 4720): vIndex = 0
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1243): device_type: 1
,D/TransactionService( 4720): Force set service start id to 1
V/TransactionService( 4720): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4720): unRegisterForConnectionStateChanges
,D/TransactionService( 4720): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4720): Destroying TransactionService
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1243): sku_id=99
,V/TransactionService( 4720): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/DraftCache( 4720): [DraftCache/463] rebuildCache
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
D/Messaging( 4720): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Jerry   ( 1243): URI_DRAFT
,D/DraftCache( 4720): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4720): [DraftCache/463] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4720): 
D/MmsAsyncWorkHandler( 4720): HM tk = 20002
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1243): sku_id=99
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1243): sku_id=99
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4696): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  911): acquireWL(4253f980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{43512d28: PendingIntentRecord{426bc940 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=125891, Int=0
,D/PMS     (  911): acquireWL(424d8bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4253f980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=15 [13][2][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(420023e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(420023e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(424d8bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42407670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,D/PMS     (  911): releaseWL(42407670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(426d4fe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1139): Change stage from stage3 to stage1
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/PMS     (  911): acquireWL(43530178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(425dce58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1226): Vacuum at: now=1453102535061 tag=VacuumService
,D/PMS     (  911): releaseWL(426d4fe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42634f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(43530178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
,D/PMS     (  911): releaseWL(425dce58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(42634f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(44372a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
D/PMS     (  911): releaseWL(44372a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(43699608): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,D/PMS     (  911): releaseWL(43699608): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4242a6e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(4242a6e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): acquireWL(435b5490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(42f46a88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42f46a88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4379eec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(435b5490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4377d5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,D/PMS     (  911): releaseWL(4377d5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1226): Scheduling Phenotype for one-off execution 10297 seconds from now (1453102535615)
,D/GetConfigurationSnapshotOperation( 1226): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1226): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1226): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1226): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  363): [NET] +++++ res_nsend xid =d707 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 253
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1139): Change stage from stage1 to stage3
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(4379eec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(430ff6c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,D/PMS     (  911): releaseWL(430ff6c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42634a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1139): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1139): nl80211: survey data missing!
E/wpa_supplicant( 1139): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1139): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025807
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025969
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026074
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026077
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026082
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026086
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027405
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030458
,D/PMS     (  911): releaseWL(42634a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44361f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/BatteryService(  911): n_update end
D/UsbnetService(  911): onReceive BATTERY_CHANGED
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(44361f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(434bd5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{4279f140: PendingIntentRecord{427c04d8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137670, Int=0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  911): releaseWL(434bd5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1332): service - mHandler: update timezone
,D/AutoSetting( 1332): service - handleMessage() stop self
,D/AutoSetting( 1539): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1539): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1332): service - handleMessage() quit looper
,D/AutoSetting( 1332): service - onDestroy() END
,D/AutoSetting( 1539): service - onCreate()
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1539): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1539): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1588): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1539): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1539): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1539): service - mHandler: update timezone
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1539): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1539): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1539): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1539): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1588): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cbb680 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 1 7 3 11
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(43cfa8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{424cdc70: PendingIntentRecord{41f1a398 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=143143, Int=0
D/PMS     (  911): acquireWL(438955b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(43cfa8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5661 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo_proxy-, success
I/global  (  911): call createSocket() return a new socket.
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4,
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  911): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  911): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  911): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  911):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  911): killProcessQuiet, pid=4356
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4356:com.htc.calendar/u0a13 (adj 15): empty #17
,D/PMS     (  911): releaseWL(438955b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  911): Recipient 4356
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  911): acquireWL(437846e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  911): sending alarm PendingIntent{423d4d20: PendingIntentRecord{42279010 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=151028, Int=0
,D/PMS     (  911): releaseWL(437846e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{43e0eae8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  911): acquireWL(425eb1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  911): Checking...
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(425eb1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1539): service - handleMessage() stop self
,D/AutoSetting( 1539): service - onDestroy() END
,D/AutoSetting( 1539): service - handleMessage() quit looper
,I/ActivityManager(  911): Killing 4371:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  911): killProcessQuiet, pid=4371
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 4371
,D/PMS     (  911): acquireWL(426f7328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10027}
,V/AlarmManager(  911): sending alarm PendingIntent{4391aab0: PendingIntentRecord{42c36180 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172960, Int=0
,D/PMS     (  911): releaseWL(426f7328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(431d2c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(431d2c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4375adb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423d4d20: PendingIntentRecord{42279010 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=211028, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4375adb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(426e3f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(426e3f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(43266878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(43266878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(436284b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423d4d20: PendingIntentRecord{42279010 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=271028, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(436284b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(43bdeee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(43bdeee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4272a990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(4272a990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43d584f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423d4d20: PendingIntentRecord{42279010 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=331029, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43d584f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4436): --= Surplus to requirements =--
I/jxcore-log( 4436): 
I/jxcore-log( 4436): ****TEST TOOK:  ms ****
I/jxcore-log( 4436): 
,I/jxcore-log( 4436): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4436): 
,E/cutils-trace( 4816): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4816): ====startRecUseTime====
D/htc.customization.log.level( 4816):  is 
,W/CustomizationLogLevel( 4816): Level value is invalid, use default level 2
,D/CustomizationManager( 4816):  Read ACC file spent 0.104 (s)
D/CIDMapFileReader( 4816): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4816): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 4816): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4816): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4816): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4816): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4816): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4816): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4816): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4816): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4816): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4816): Parsing tag category name = system
,I/CustomizationCIDLoader( 4816): Parsing tag category name = application
I/CustomizationCIDLoader( 4816): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4816): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4816): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 4816): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4816): Parsing tag category name = Settings
D/CustomizationManager( 4816):  Read CID file spent 0.156 (s)
,D/CustomizationManager( 4816):  All configurations done spent 0.156 (s),
,W/HtcNativeFlag( 4816): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4816): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4816): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4816): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4816, uid=2000 user=0
,I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  911): killProcessQuiet, pid=4436
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  911): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  911): Killing 4436:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  911):   Force finishing activity ActivityRecord{42451e08 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  911): Copying FileAsset 0x6506d268 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1212): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  911): Got RemoteException sending setActive(false) notification to pid 4436 uid 10389
,W/PackageSettings(  911): Skipping PackageSetting{421f6cc0 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,W/InputDispatcher(  911): channel '4328c840 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  911): channel '4328c840 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  911): Attempted to unregister already unregistered input channel '4328c840 com.test.thalitest.MainActivity (s)'
I/WindowManager(  911): WINDOW DIED Window{4328c840 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  911): Client connection lost with reason: 4
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WindowManager(  911): Failed looking up window
W/WindowManager(  911): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@425c4c38 does not exist
W/WindowManager(  911): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  911): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  911): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  911): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  911): 	at dalvik.system.NativeStart.run(Native Method)
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
,D/DotMatrix( 1588): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/DotMatrix( 1588): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/WindowState(  911): WIN DEATH: null
,W/GeofencerStateMachine( 1226): Ignoring removeGeofence because network location is disabled.
,D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  911): acquireWL(431c2d98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  911): releaseWL(431c2d98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
D/VoicemailCleanupService( 1303): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/[PluginManager]RegisterService( 1332): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1332): handle notify Blinkfeed plugin client changed
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
,I/IcingCorporaProvider( 2853): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4832 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  911): acquireWL(424cd1a0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2853): UpdateCorporaTask done [took 246 ms] updated apps [took 246 ms] 
,E/SQLiteDatabase( 4832): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4832): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4832): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4832): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4832): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4832): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4832): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4832): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4832): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4832): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4832): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4832): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4832): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4832): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4832): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4832): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4832): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4832): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4832): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4832): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4832): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4832): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4832): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4832): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4832): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4832): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4832): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4832): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4832): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4832): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4832): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4832): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4832): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4832): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4832): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4832): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4832): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4832): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4832): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4832): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4832): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4832): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4832): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4832): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4832): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4832): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4832): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4832): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4832): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4832): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4832): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4832): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4832): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4832): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4832): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4832): threadid=11: thread exiting with uncaught exception (group=0x41735e30)
,E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4832): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4832): Process: com.google.android.apps.docs, PID: 4832
E/AndroidRuntime( 4832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4832): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4832): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4832): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4832): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4832): 	at aho.run(AbstractDatabaseInstance.java:455)
,D/Process ( 4832): killProcess, pid=4832
,D/Process ( 4832): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4850 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  911): Recipient 4832
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4832) has died.
,W/ContextImpl( 4850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4863 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4850): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4850): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4850): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4850): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4850): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4850): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4850): threadid=10: thread exiting with uncaught exception (group=0x41735e30)
,E/ActivityManager(  911): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4850): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4850): Process: com.android.keychain, PID: 4850
E/AndroidRuntime( 4850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4850): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4850): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4850): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4850): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4850): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
,D/AppTag  ( 4863): getInstance(Context context)
,D/Process ( 4850): killProcess, pid=4850
,D/Process ( 4850): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453102753132.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  911): Recipient 4850
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Process com.android.keychain (pid 4850) has died.
,D/AppTag  ( 4863): getInstance(Context context)
,W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4863): onCreate()
,D/PMS     (  911): acquireWL(426c23a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4034 10160 null
,D/PMS     (  911): releaseWL(426c23a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Process (  911): killProcessQuiet, pid=4001
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/dalvikvm( 4078): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  911): Killing 4001:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2184): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6ec5a778
,E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cb4c830
,W/dalvikvm( 2184): threadid=47: thread exiting with uncaught exception (group=0x41735e30)
,E/DriveAsyncService( 2184): disk I/O error (code 3850)
E/DriveAsyncService( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2184): 	at java.lang.Thread.run(Thread.java:864)
,E/AndroidRuntime( 2184): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2184): Process: com.google.android.gms, PID: 2184
E/AndroidRuntime( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2184): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2184): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2184): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2184): 	at java.lang.Thread.run(Thread.java:864)
I/LocationSettingsChecker( 2184): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager(  911): App crashed! Process: com.google.android.gms
,E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 2184): killProcess, pid=2184
,D/Process ( 2184): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/ActivityManager(  911): Recipient 4001
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bfacb0 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/ActivityManager(  911): Recipient 2184
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.gms (pid 2184) has died.
D/PMS     (  911): handleWLDeath(424cd1a0): PARTIAL_WAKE_LOCK  Icing 0x1
,D/WifiService(  911): Client connection lost with reason: 4
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 21000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
,I/ActivityManager(  911): Resuming delayed broadcast
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20997ms
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30996ms
,E/SQLiteLog( 1372): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1372): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5c9f7808
,W/dalvikvm( 1372): threadid=1: thread exiting with uncaught exception (group=0x41735e30)
,E/ActivityManager(  911): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1372): FATAL EXCEPTION: main
E/AndroidRuntime( 1372): Process: com.google.process.gapps, PID: 1372
E/AndroidRuntime( 1372): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1372): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1372): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1372): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1372): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1372): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1372): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1372): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1372): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1372): 	... 10 more
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
,D/Process ( 1372): killProcess, pid=1372
W/PackageManager(  911): Unable to load service info ResolveInfo{42653ac8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/Process ( 1372): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  911): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4895 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4895): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4895 dbg=false s=true
,I/DeviceManagement( 4895): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4895): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4895): WorkflowService: Starting workflow service
I/ActivityManager(  911): Recipient 1372
D/WifiService(  911): Client connection lost with reason: 4
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.process.gapps (pid 1372) has died.
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30837ms
I/DeviceManagement( 4895): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b9dfb0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4895): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4895): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4895): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4895): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  911): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4909 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4895): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4895): SessionStateController: Checking invariants...

```
