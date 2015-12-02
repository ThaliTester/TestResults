#### Test 5198634075bb434_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  906): mEventCount = 900
--------- beginning of /dev/log/system
I/ActivityManager(  906): Waited long enough for: ServiceRecord{44330170 u0 com.htc.htclocationservice/.AutoSettingService}
,D/CustomizationManager( 4443): ====startRecUseTime====
D/htc.customization.log.level( 4443):  is 
W/CustomizationLogLevel( 4443): Level value is invalid, use default level 2
D/CustomizationManager( 4443):  Read ACC file spent 0.059 (s)
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
D/CustomizationManager( 4443):  Read CID file spent 0.098 (s)
D/CustomizationManager( 4443):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 4443): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4443): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4443): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4443): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4443
D/PMS     (  906): acquireHCC(4282c7a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(427f92d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x65861f90 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1120169160
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
E/cutils-trace( 4443): Error opening trace file: No such file or directory (2)
D/PMS     (  906): acquireWL(424ce068): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@424a8530
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4454 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1267): [trimMemory] 20
W/asset   ( 4454): Copying FileAsset 0x5c78a648 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4454): Binding Chromium to main looper Looper (main, tid 1) {41ddccc8}
I/LibraryLoader( 4454): Expected native library version number "",actual native library version number ""
I/chromium( 4454): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4454): Initializing chromium process, renderers=0
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426933a8:true
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4454): 1105146120: getState(). Returning 12
D/PMS     (  906): acquireWL(4214dfa8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): acquireWL(41ef6fe0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(41ef6fe0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4454): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4454): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4454): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4454): Local Branch: 
I/Adreno-EGL( 4454): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4454): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4454):                  aa63bbd948f41d15fc72f585e
W/chromium( 4454): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4454): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4454): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4454): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4454): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4454): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4454): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4454): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4454): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4454): CordovaWebView is running on device made by: HTC
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,W/AwContents( 4454): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1267
,W/ResourceType( 4454): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4454): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41e247b8, mServedView=org.apache.cordova.engine.SystemWebView{41dea420 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=4454
,W/AwContents( 4454): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +280ms
,D/PMS     (  906): releaseWL(424ce068): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4454): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4454): JniHelper::setJavaVM(0x4199a010), pthread_self() = 1662545640
,D/JX-Cordova( 4454): jxcore cordova android initializing
,W/dalvikvm( 4454): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.560MB for 98002-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.619MB for 146998-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.723MB for 220492-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.902MB for 330734-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 12.180MB for 496096-byte allocation
,D/PMS     (  906): acquireWL(423ea9c0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(423ea9c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(427f38d0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(427f38d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(428703a0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 13.203MB for 1116206-byte allocation
D/PMS     (  906): releaseWL(428703a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  906): acquireWL(43f01348): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(43f01348): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 14.086MB for 1674304-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 15.499MB for 2511452-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 17.536MB for 3767174-byte allocation
,W/jxcore-log( 4454): Initializing JXcore engine
,W/jxcore-log( 4454): JXcore engine is ready
,W/jxcore-log( 4454): Starting JXcore engine
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(4282c7a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(427f92d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
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
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
D/WifiService(  906): setWifiEnabled: true pid=4454, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
D/WifiService(  906): New client listening to asynchronous messages
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1761
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 3(ms)
D/WifiManager( 4454): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4454): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): TDLS: Tear down peers
I/wpa_supplicant( 1175): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4454): Radios toggled
I/jxcore-log( 4454): 
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1175): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
,I/wpa_supplicant( 1175): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
,D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1175): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/Tethering(  906): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1175): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8626bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1175):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1175): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1175): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP,])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1175): nl80211: Event message available
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1175): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1175): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2462
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2462
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(437946e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  906):    returned true
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): Fast associate: Old scan results
I/wpa_supplicant( 1175): wpa_supplicant_scan enter
I/wpa_supplicant( 1175): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1175): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1175): wpa_supplicant_trigger_scan +
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1175): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19219 mDataStallAlarmIntent=PendingIntent{428193f8: PendingIntentRecord{428607c0 android broadcastIntent}}
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
,D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1874/10178)
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
,D/WISPrService( 4223): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiService(  906): New client listening to asynchronous messages
,D/WISPrService( 4223): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4223): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] entry_id:5   entry:0xb7f008e0  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb7f01000  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb7f052f0  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb7f05108  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb7f011a8  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb7f04fd8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb7f05410  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/PMS     (  906): acquireWL(4422d690): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WISPrService( 4223): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(433365d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/PMS     (  906): acquireWL(42969140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  906): releaseWL(42969140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1874/10178)
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  906):    returned false
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1364/10028)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  906): releaseWL(4422d690): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,D/PMS     (  906): releaseWL(433365d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,D/PMS     (  906): releaseWL(4214dfa8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4509 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(42873fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{4282c7d0: PendingIntentRecord{4286ec70 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449063155398, Int=60000
D/PMS     (  906): releaseWL(42873fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4509): SMSBackupAgentService started
,D/SMSBackup( 4509): Checking restore status
D/SMSBackup( 4509): Restore complete
,D/SMSBackup( 4509): cancelCheckAlarm
,D/SMSBackup( 4509): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3685
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3685:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3685
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1417/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/NetworkMonitor( 3945): type=WIFI subType= reason=null isConnected=false
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  906): NoActiveNetworkState
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3945/10154)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43db9548): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1912/1000)
D/PMS     (  906): releaseWL(43db9548): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4344/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1874/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4344/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2021/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4523 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4523): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4523): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4523): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4523): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4523): Preparing secondary program dexes.
V/DexLibLoader( 4523): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4523): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4523): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4523): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4523): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4523): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4523): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4523): Creating class loader
,V/DexLibLoader( 4523): Finished creating class loader
V/DexLibLoader( 4523): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar,
V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4523): Creating class loader,
V/DexLibLoader( 4523): Finished creating class loader
V/DexLibLoader( 4523): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4523): Dex already copied
,D/OdexVerifier( 4523): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4523): Creating class loader
V/DexLibLoader( 4523): Finished creating class loader
V/DexLibLoader( 4523): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4523): Dex already copied,
D/OdexVerifier( 4523): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4523): Creating class loader
V/DexLibLoader( 4523): Finished creating class loader
,V/DexLibLoader( 4523): Verifying classes from secondary dexes.
,D/DexLibLoader( 4523): DexLibLoader.ensureDexLoaded took 18 ms,
,W/dalvikvm( 4523): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1175): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1175): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1175): nl80211: Survey data missing
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1175): Sorted scan results
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1175): [NULL] c2:ff:d4:d3:aa:48 freq=2462 level=-46
I/wpa_supplicant( 1175): [NULL] c0:ff:d4:d3:aa:48 freq=2462 level=-47
I/wpa_supplicant( 1175): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
I/wpa_supplicant( 1175): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1175): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-83
I/wpa_supplicant( 1175): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1175): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1175): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1175): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1175): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1175): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1175): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1175): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1175): Add randomness: count=14 entropy=6
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1175): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1175): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1175): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1175): wpa_supplicant_pick_network+
I/wpa_supplicant( 1175): Selecting BSS from priority group 1
I/wpa_supplicant( 1175): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1175): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1175): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1175): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie,_len=0 caps=0x431
W/wpa_supplicant( 1175): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1175):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1175):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462 rssi=-47
I/wpa_supplicant( 1175): Start print parameters
I/wpa_supplicant( 1175): wpa_s->wpa_state is 3
I/wpa_supplicant( 1175): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1175): isConcurrentMode() is 0
I/wpa_supplicant( 1175): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1175): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1175): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1175): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1175): wpa_s->reassociate is 1
I/wpa_supplicant( 1175): wpa_s->is_screen_on 1
I/wpa_supplicant( 1175): wpa_s->ifname wlan0
I/wpa_supplicant( 1175): End print parameters
I/wpa_supplicant( 1175): selected network = 1
D/wpa_supplicant( 1175): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb86284e8  current_ssid=0x0
D/wpa_supplicant( 1175): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1175): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1175): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1175): check if in concurrent case
I/wpa_supplicant( 1175): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1175): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1175): RSN: PMKSA cache search - network_ctx=0xb86284e8 try_opportunistic=0
,D/wpa_supplicant( 1175): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1175): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1175): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1175): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2462 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1175): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1175): nl80211: Unsubscribe mgmt frames handle 0xb8627718 (mode change)
D/wpa_supplicant( 1175): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8627718
,D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1175): nl80211: Register frame type=0xd0 nl_handle=0xb8627718
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1175): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1175):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1175):   * freq=2462
D/wpa_supplicant( 1175):   * Auth Type 0
D/wpa_supplicant( 1175):   * WPA Versions 0x2
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1175): nl80211: Connect request send successfully
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1175): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1175): reply (925) for get BSS: id=0,
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1175): freq=5220
I/wpa_supplicant( 1175): level=-50
I/wpa_supplicant( 1175): tsf=0000000105271240
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG7005g
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=1
I/wpa_supplicant( 1175): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2462
I/wpa_supplicant( 1175): level=-47
I/wpa_supplicant( 1175): tsf=0000000105271258
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=NG700
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=2
I/wpa_supplicant( 1175): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1175): freq=2412
I/wpa_supplicant( 1175): level=-82
I/wpa_supplicant( 1175): tsf=0000000105271273
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1175): ssid=Gonzos
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=3
I/wpa_supplicant( 1175): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-82
I/wpa_supplicant( 1175): tsf=0000000105271277
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1175): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=4
I/wpa_supplicant( 1175): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-83
I/wpa_supplicant( 1175): tsf=0000000105271263
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=UPC4688432
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=5
I/wpa_supplicant( 1175): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): freq=2462,
I/wpa_supplicant( 1175): level=-46
I/wpa_supplicant( 1175): tsf=0000000105271253
I/wpa_supplicant( 1175): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1175): ssid=01ABC
I/wpa_supplicant( 1175): ====
I/wpa_supplicant( 1175): id=6
I/wpa_supplicant( 1175): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1175): freq=2437
I/wpa_supplicant( 1175): level=-85
I/wpa_supplicant( 1175): tsf=0000000105271267
I/wpa_supplicant( 1175): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1175): ssid=UPC5999698
I/wpa_supplicant( 1175): ####
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 105271240, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2462, timestamp: 105271258, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 105271273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -82, frequency: 2437, timestamp: 105271277, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -83, frequency: 2437, timestamp: 105271263, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -46, frequency: 2462, timestamp: 105271253, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 105271267, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4523): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1175): Wireless event: cmd=0x8b15 len=20
,D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1175): nl80211: Event message available
D/wpa_supplicant( 1175): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1175): nl80211: Connect event
D/wpa_supplicant( 1175): nl80211: Associated on 2462 MHz
D/wpa_supplicant( 1175): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1175): nl80211: Operating frequency for the associated BSS from scan results: 2462 MHz
I/wpa_supplicant( 1175): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1175): Add randomness: count=15 entropy=7
I/wpa_supplicant( 1175): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/wpa_supplicant( 1175): TDLS: Remove peers on association
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1175): EAPOL: enable timer tick
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1175): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1175): Get randomness: len=32 entropy=8
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2462
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2462
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
,D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/wpa_supplicant( 1175): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb86279f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1175):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1175): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f91b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1175):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1175): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1175): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1175): State: GROUP_HANDSHAKE -> COMPLETED
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1175): setConcurrentAPChannel: Set wifi.hotspot.channel to 11
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1175): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1175): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1175): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1175): set send_ind_to_ndc = 0
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1175): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1175): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1175): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1175): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1175): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1175): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1175): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1175): EAPOL authentication completed successfully
I/wpa_supplicant( 1175): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1175): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1175): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1175): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  906): updateConnectedAP...,
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2462
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2462, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WISPrService( 4223): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4223): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2462, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 1
,I/wpa_supplicant( 1175): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42826860): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42741e78 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42741e78 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4523): Verify
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4454): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): my name is : HTC-HTC Desire 820_PT6761
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): attempting to connect to test coordinator
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): check test folder
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): found test : ./testFindPeers.js
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): found test : ./testReConnect.js
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): found test : ./testSendData.js
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): Test app app.js loaded
I/jxcore-log( 4454): 
,I/Choreographer( 4454): Skipped 159 frames!  The application may be doing too much work on its main thread.
D/WifiService(  906): New client listening to asynchronous messages
,I/chromium( 4454): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4523): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4523): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3230
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3230:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3230
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(433f2fb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
,D/PMS     (  906): acquireWL(436d1398): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(433f2fb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
D/PMS     (  906): releaseWL(436d1398): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1389): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4552 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1389/10053)
,D/AutoSetting( 1389): Util - no network available!
,D/AutoSetting( 1389): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1389): service - mHandler: cancel location update
,D/AutoSetting( 1389): service -           changes count: 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1389/10053)
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4523): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4552): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4552): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4552): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4552): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4566 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4275
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4275:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4552/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4552/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4552/10078)
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  906): Recipient 4275
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/WifiService(  906): Client connection lost with reason: 4
,E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4523): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4523): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4523): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4523): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4523): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4523): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4523): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4523): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4523): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4523): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4523): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4523): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4523): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4583 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3928
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3928:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 9.927MB for 39954-byte allocation
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4583): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4583): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Recipient 3928
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.003MB for 79892-byte allocation
,W/GAV2    ( 4583): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4583): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4583): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.067MB for 84664-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4583/10151)
,V/WebViewChromiumFactoryProvider( 4583): Binding Chromium to main looper Looper (main, tid 1) {41de2368}
,I/LibraryLoader( 4583): Expected native library version number "",actual native library version number ""
,I/chromium( 4583): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4583): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4583): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(43c2d930): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): acquireWL(43f99350): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(43c2d930): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4583): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4583/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4583/10151)
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4201/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4201/10160)
,D/Process (  906): killProcessQuiet, pid=4313
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4313:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1874/10178)
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1874/10178)
I/ActivityManager(  906): Recipient 4313
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4392ab68 u0 ReceiverList{4392aa68 4523 com.facebook.katana/10026/u0 remote:4382a3c0}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4392ab68 u0 ReceiverList{4392aa68 4523 com.facebook.katana/10026/u0 remote:4382a3c0}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ee27f8 u0 ReceiverList{43ee27b8 4523 com.facebook.katana/10026/u0 remote:43e5e348}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/PMS     (  906): acquireWL(43a383a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1417 10028 null
,D/PMS     (  906): releaseWL(43a383a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1417): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(42748568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1417 10028 null
D/PMS     (  906): releaseWL(42748568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1175): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1175): EAPOL: disable timer tick
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1175): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  906): releaseWL(42826860): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1175): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -46, Link speed: 72, Frequency: 2462, Net ID: 0, Metered hint: false
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19221 delay=15s
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 4223): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1874/10178)
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=false
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@427289c0
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:2
,D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  906): acquireWL(4388d1c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4552/10078)
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(437ea4f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4388d1c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  906): acquireWL(437bf5c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
D/PMS     (  906): releaseWL(437ea4f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
I/CheckinService( 1222): Preparing to send checkin request
,I/EventLogService( 1222): Accumulating logs since 1449063105549
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
I/GoogleHttpClient( 1222): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1222): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1222): awaiting user notification for token
,D/DotMatrix( 1580): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e43478 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 7 3 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4659 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4659): install
,I/MultiDex( 4659): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4659): loading existing secondary dex files
,I/MultiDex( 4659): load found 1 secondary dex files
,I/MultiDex( 4659): install done
,I/ProviderInstaller( 4659): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/Adreno-EGL( 4659): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4659): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4659): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4659): Local Branch: 
I/Adreno-EGL( 4659): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4659): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4659):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4659): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4659): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4659): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4659): Local Branch: 
I/Adreno-EGL( 4659): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4659): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4659):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4659): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4659): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4659): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4659): Local Branch: 
I/Adreno-EGL( 4659): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4659): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4659):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  906): releaseWL(437946e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  906): NoActiveNetworkState
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTED
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
I/acms    ( 1912): Checking Certificates
I/acms    ( 1912): Checking Developer Certificates
I/acms    ( 1912): Checking Application Certificates
I/acms    ( 1912): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1912): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1912): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43aa6690): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(43aa6690): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1417/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1874/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4344/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1912/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4552/10078)
I/acms    ( 1912): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1912): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1912): Updating next query delay: 75600000
I/mlserverapp( 1912): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1912): cancelACMSProgrammedChecks
,I/NetworkMonitor( 3945): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3945/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3966/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(436d98c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
D/PMS     (  906): releaseWL(436d98c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4344/10100)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2021/10021)
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(430b7ed8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,I/SensorManager(  906): mEventCount = 1050
D/PMS     (  906): releaseWL(430b7ed8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): acquireWL(442f1820): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1364 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1364): [NET] getaddrinfo-,err=8
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1364): [NET] getaddrinfo-, 1
D/libc    ( 1364): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a75a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/AutoSetting( 1389): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1389): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1389): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1389): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1389): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1389): service - handleMessage() setting current location null
,D/AutoSetting( 1389): Util - check NLP state, Allowned:false, Enabled:false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1389/10053)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1389/10053)
D/AutoSetting( 1389): service - onStartCommand() check timezone in 30000
D/MobileConnectivityChangeReceiver( 4552): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4552): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4583/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4201/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4201/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1874/10178)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 202
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1364): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4201): Grow heap (frag case) to 13.519MB for 1821008-byte allocation
,D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1364): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): acquireWL(4308de40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  906): releaseWL(4308de40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1364): Connected
D/PMS     (  906): acquireWL(43b9d3c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): releaseWL(442f1820): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): releaseWL(43b9d3c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(427bd488): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1364): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): acquireWL(4432e530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  906): releaseWL(427bd488): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): releaseWL(4432e530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4659): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4659/10028)
,I/CheckinTask( 1222): Sending checkin request (9171 bytes)
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =dd59 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=11 [9][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-47 , oldRssi= -200
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 250
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4523): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026),
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(442f6460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(442f6460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=0 [1][0][0]
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1580): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1222): awaiting user notification for token
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e43b08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 7 2 12
,I/CheckinTask( 1222): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1222): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(437bf5c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1222): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e12590 that was originally bound here
E/ActivityThread( 1222): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e12590 that was originally bound here
E/ActivityThread( 1222): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1222): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1222): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1222): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1222): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1222): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1222): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1222): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1222): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1222): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1222): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1222): 	at bks.a(SourceFile:298)
E/ActivityThread( 1222): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1222): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1222): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1222): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1364): GCM config loaded
,D/PMS     (  906): releaseWL(43f99350): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4240d760
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,W/BatSI   (  906): Couldn't get kernel wake lock stats
W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4240d760, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421ad780
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@41ef6cf8
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f8ba +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 376ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/NfcService( 1250): ScreenObserver: OFF
,D/NfcService( 1250): applyRouting - 0
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/HABCtrl (  906): TPE algorithm. remove timeout.
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4454
,D/NfcService( 1250): applyRouting -2
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43c1ed80)
W/ResourceType( 4454): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4454): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41dea420 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  906): acquireWL(43b91750): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1250 1027 null
D/PMS     (  906): releaseWL(43b91750): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): wakingUp
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
I/WindowManager(  906): No lock screen! windowToken=null
,D/PMN     (  906): onScreenOn
D/PMS     (  906): acquireWL(4394b0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(4394b0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2021): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1250): applyRouting - 0
,D/MtpService( 2021): [MTP][onReceive]-
,D/NfcService( 1250): applyRouting -2
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): acquireWL(43c20e90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1250 1027 null
D/AlarmManager(  906): ACTION_SCREEN_ON
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): releaseWL(43c20e90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/AutoSetting( 1389): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1389): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/ClockThread( 1115): stop update clock
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
D/TetherSettings( 4223): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4223): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4223): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4223): Cust_ConnectToPC   : spcsc>false
D/        ( 4223): Cust_ConnectToPC   : IPT>true
,D/        ( 4223): Cust_ConnectToPC   : Singel_USB>false
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19222 delay=15s
,W/Settings( 4223): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4223): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4223): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4223): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): SET_SCREEN_ON:On
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1175): htc_wext_set_TX_TRACKING - ret = 0
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,I/PSReceiver( 4223): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4223): onReceive:android.intent.action.USER_PRESENT
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 4223): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4223): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4223):  defaultType:0
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1175): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,V/SRS_Proc(  372): ParamSet string: screen_state=on
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1175): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/NetworkPolicy(  906): updateScreenOn: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4703 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/jxcore-log( 4454): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4454): 
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(42691480): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
,D/PMS     (  906): releaseWL(42691480): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1845): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1845): onScreenOn: 1449063162222
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1845): onScreenOn: 1449063162222
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421ad780
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
,W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421ad780, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@41ef6cf8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(442f1250): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): releaseWL(442f1250): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19222 mDataStallAlarmIntent=PendingIntent{421d5040: PendingIntentRecord{42cb2ac0 android broadcastIntent}}
,D/PMS     (  906): acquireWL(43a12fe8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4703 1000 null
,D/SmartSyncUtils( 4703): isEpsOn(), nState = 0
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1175): SET_SCREEN_ON:Off
I/wpa_supplicant( 1175): htc_wext_set_keepalive +
I/wpa_supplicant( 1175): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1175): getPrivFuncNum +	
I/wpa_supplicant( 1175): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1175): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1175): get_ip_address source addr = c0a8016c
I/wpa_supplicant( 1175): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1175): htc_wext_set_keepalive - ret = 0,
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(428dcb50): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/NetworkPolicy(  906): updateScreenOn: false
,D/PMS     (  906): releaseWL(43a12fe8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4703): getMobilePolicyEnabled, result = true
,D/Process (  906): killProcessQuiet, pid=4344
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 4344:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/PMS     (  906): releaseWL(428dcb50): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/SmartSyncUtils( 4703): isEpsOn(), nState = 0
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
D/SmartSyncUtils( 4703): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4703): getMobilePolicyEnabled, result = true
D/WifiService(  906): New client listening to asynchronous messages
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ef6cf8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
,W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ef6cf8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ef6cf8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ef6cf8
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42708b60 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42708b60 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
D/ContactMessageStore( 1242): Background delete complete
D/AutoSetting( 1389): service - mHandler: cancel location update
D/AutoSetting( 1389): service -           changes count: 0
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(43bc7848): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1845): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1845): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1845): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1845): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1845): onScreenOff
D/PMS     (  906): releaseWL(43bc7848): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  906): Recipient 4344
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4583): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(4450f368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1417 10028 null
,D/PMS     (  906): acquireWL(4450f1a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1417 10028 null
,D/PMS     (  906): releaseWL(4450f368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(4450f1a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/Process (  906): killProcessQuiet, pid=4367
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4367:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4367
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1509): service - handleMessage() stop self
,D/AutoSetting( 1509): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4385
,I/ActivityManager(  906): Killing 4385:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1509): service - handleMessage() quit looper
,I/ActivityManager(  906): Recipient 4385
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.941MB for 18476-byte allocation
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.956MB for 27710-byte allocation
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.977MB for 41560-byte allocation
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 11.010MB for 62336-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 11.055MB for 66142-byte allocation
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 11.055MB for 44214-byte allocation
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 11.087MB for 57348-byte allocation
,D/libc    ( 4523): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4523): [NET] getaddrinfo-,err=8
D/libc    ( 4523): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4523): [NET] getaddrinfo-, 1
,D/libc    ( 4523): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =b71d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 58
D/libc    (  365): [NET]res_nsend:resplen=93
D/libc    (  365): [NET]res_queryN: exit 3, ancount=3
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4523): [NET] getaddrinfo_proxy-, success
I/global  ( 4523): call createSocket() return a new socket.
D/libc    ( 4523): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
,D/libc    ( 4523): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4523): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4523): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(44309280): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4523 10026 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4523/10026)
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 11.207MB for 57398-byte allocation
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4523): I/O error closing connection
I/global  ( 4523): java.net.SocketException: Socket is closed
I/global  ( 4523): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4523): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4523): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4523): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4523): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4523): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4523): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4523): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4523): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4523): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4523): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4523): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4523): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4523): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4523): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4523): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4523): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4523): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4523): Removing a connection that never existed!
D/PMS     (  906): releaseWL(44309280): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(442c71c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=128371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(442c71c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(442855c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(442855c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/AutoSetting( 1389): service - mHandler: update timezone
,D/AutoSetting( 1509): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1509): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1509): service - onCreate()
,D/AutoSetting( 1509): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1509): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/DotMatrix( 1580): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1509): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1509): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1509): service - mHandler: update timezone
,D/AutoSetting( 1509): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1509): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1509): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1509): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1580): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41f2df00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 8 2 11
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/AutoSetting( 1389): service - handleMessage() stop self
,D/PMS     (  906): acquireWL(43ac7050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
V/AlarmManager(  906): sending alarm PendingIntent{4214c698: PendingIntentRecord{427f64a0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140741, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42648088: PendingIntentRecord{42749dd0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140788, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  906): acquireWL(43a9d468): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(43ac7050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(43a979b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/AutoSetting( 1389): service - handleMessage() quit looper
,D/AutoSetting( 1389): service - onDestroy() END
D/PMS     (  906): releaseWL(43a979b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =575e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/Process (  906): killProcessQuiet, pid=3966
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3966:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,D/PMS     (  906): releaseWL(43a9d468): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  906): Recipient 3966
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4382ee58 u0 com.htc.htclocationservice/.AutoSettingService}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1509): service - handleMessage() stop self
,D/AutoSetting( 1509): service - onDestroy() END
,D/AutoSetting( 1509): service - handleMessage() quit looper
,I/ActivityManager(  906): Killing 4401:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4401
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4401
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(427bb848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427bb848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4237e5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=188372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4237e5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42047368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(42047368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(43805308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43f26660: PendingIntentRecord{42f7cbd0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226253, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4745 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42573988: PendingIntentRecord{4234b860 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449063271211, Int=10800000
,D/PMS     (  906): releaseWL(43805308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4745/10047)
,D/Process (  906): killProcessQuiet, pid=4416
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4416:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4416
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(422dd830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/PMS     (  906): releaseWL(422dd830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,D/PMS     (  906): acquireWL(4233f8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4286e930: PendingIntentRecord{42f7cbd0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230620, Int=0
,D/PMS     (  906): releaseWL(4233f8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42980b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=248371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42980b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4282fda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4282fda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42716788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42716788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4287e5e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=308372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4287e5e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4284ec38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4284ec38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42942ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{4421e210: PendingIntentRecord{443576d0 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1449063408892, Int=0
,D/PMS     (  906): releaseWL(42942ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 1222): No account for auth token provided
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ff8 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 291
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
I/global  ( 1222): call createSocket() return a new socket.
D/libc    ( 1222): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1580): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{420f1d90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4164): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4164): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4164): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4164): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4164): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4164): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4164): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4164): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 12 3 12
,D/libc    ( 4164): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4164): [NET] getaddrinfo-,err=8
D/libc    ( 4164): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4164): [NET] getaddrinfo-, 1
,D/libc    ( 4164): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =b3d2 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4164): [NET] getaddrinfo_proxy-, success
I/global  ( 4164): call createSocket() return a new socket.
D/libc    ( 4164): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4164): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4164): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4164): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(42678630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=368372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42678630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4394b3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4394b3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(430b7d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(430b7d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(426fb318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=428371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426fb318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(435c2710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(435c2710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(438aa7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(438aa7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(429e6ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=488372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429e6ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43d74aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43d74aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(438a5680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43b291c8: PendingIntentRecord{4434a010 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=410326, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{4209f990: PendingIntentRecord{42794a28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=512373, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{43e573a0: PendingIntentRecord{41e1f980 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449063514705, Int=1800000
,D/PMS     (  906): acquireWL(42f25e50): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4436b7d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): acquireWL(4265a990): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(42f25e50): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(4436b7d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): releaseWL(438a5680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(442f5580): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(4265a990): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1222): Aggregate from 1449063158666 (log), 1449061714663 (data)
,D/PMS     (  906): releaseWL(442f5580): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/Atfwd_Sendcmd(  389): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4284a030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=548371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4284a030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42cdc038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42cdc038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4287f028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4287f028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4434c700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=608371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4434c700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42959920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42959920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1242): sku_id=99
D/ContactMessageStore( 1242): start background delete task...
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(438050e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=668371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438050e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42939240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42939240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/Process (  906): killProcessQuiet, pid=4077
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4077:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4077
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4308e880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=728371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4308e880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a9b9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(43a9b9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(434f2780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(434f2780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4435bdd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43b291c8: PendingIntentRecord{4434a010 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=710326, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{420cb920: PendingIntentRecord{427332e0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785164, Int=0
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): releaseWL(4435bdd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(442f5e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=788371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(442f5e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44359c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44359c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(442f1d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(442f1d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42808380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=848371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42808380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4424c878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(4424c878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(43746c18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(43746c18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4396ff60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=908371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4396ff60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(44371850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44371850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(435098d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=968371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435098d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(442d1e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(442d1e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(43190a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{44285840: PendingIntentRecord{4282e458 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1008358, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{42667cc0: PendingIntentRecord{42667c40 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449063991571, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{42155f18: PendingIntentRecord{43ee39f0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449064062315, Int=0
,D/PMS     (  906): acquireWL(42c46fc0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(42c46fc0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): acquireWL(42d77610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(42d77610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4703): call getInstance()
,D/SmartSyncUtils( 4703): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4703): MY_DEBUG = false
,D/PMS     (  906): acquireWL(44349120): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4703 1000 null
,D/PMS     (  906): releaseWL(43190a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4703): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4703): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 0, nStart = 20, nEnd = 0, bNormalRange = true
,D/PMS     (  906): acquireWL(442c9a80): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/SmartSyncScreenOnOffTimeReceiver( 4703): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4703): SettingOnTime = 1449097200000, randomSettingOnTime = 1449095077000
D/SmartSyncScreenOnOffTimeReceiver( 4703): SettingOffTime = 1449082800000, randomSettingOffTime = 1449083682000
D/SmartSyncScreenOnOffTimeReceiver( 4703): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4703): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4703): bNightModeTurnOffOnce = false
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/PMS     (  906): releaseWL(44349120): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  906): releaseWL(442c9a80): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(442e6c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  906): releaseWL(442e6c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
W/BatSI   (  906): Couldn't get kernel wake lock stats
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=10 [394][41][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1175): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1175): nl80211: survey data missing!
E/wpa_supplicant( 1175): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1175): environment dirty rate=0 [0][0][0]
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(428b15b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PMS     (  906): releaseWL(428b15b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42c2b190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1028372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c2b190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(438e4f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(438e4f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4280e8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4280e8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(44322f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1088372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44322f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(43a9c808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43a9c808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(420ef778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(420ef778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42970500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1148371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42970500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4290af08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4290af08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(437fbf60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1208372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437fbf60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4290a478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4290a478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(423f0120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423f0120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(438a4b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1268372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438a4b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(426be900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/PMS     (  906): releaseWL(426be900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(433d21f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(433d21f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=98
,D/DotMatrix( 1580): [EventService] reorderNotification, total:1
D/HeadsetPhoneState( 1600): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,D/TetherSettings( 4223): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4223): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4223): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4223): Cust_ConnectToPC   : spcsc>false
D/        ( 4223): Cust_ConnectToPC   : IPT>true
D/        ( 4223): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4223): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4223): Index of the first 1 = -1
W/ContextImpl( 4223): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 4223): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4223): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4223): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4223): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4223): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4223): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(438a7888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1328371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438a7888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(43eb7940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43eb7940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=98
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4270e8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4270e8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42c8d368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1388372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c8d368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4435e288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): releaseWL(4435e288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=98
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(43909dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43909dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(427bc878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1448371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427bc878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437d0820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437d0820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42185c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1508372, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42185c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a1c678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43a1c678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(430a4eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430a4eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4344a2e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1568371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4344a2e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4286bb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4286bb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(442dd6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1628371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(442dd6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(433ffd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(433ffd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(42824750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1688371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42824750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437288b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437288b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(426acf08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
V/NotificationService(  906): batLight: Full, plugged
D/PMS     (  906): releaseWL(426acf08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
D/DotMatrix( 1580): [EventService] reorderNotification, total:0
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1600): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/TetherSettings( 4223): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4223): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4223): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4223): Cust_ConnectToPC   : spcsc>false
D/        ( 4223): Cust_ConnectToPC   : IPT>true
D/        ( 4223): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4223): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4223): Index of the first 1 = -1
W/Settings( 4223): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4223): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4223): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4223): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4223): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4223): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(4378d1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1748371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4378d1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4281bc00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4281bc00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(43d60af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1808371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43d60af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b8aa88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b8aa88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(443773f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{420cb920: PendingIntentRecord{427332e0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505198, Int=0
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ProcessStatsService(  906): Prepared write state in 43ms
,I/ProcessStatsService(  906): Prepared write state in 21ms
,V/AlarmManager(  906): sending alarm PendingIntent{426b9648: PendingIntentRecord{427e0e88 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820312, Int=1800000
,D/PMS     (  906): acquireWL(43a86160): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{42667cc0: PendingIntentRecord{42667c40 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449064891571, Int=900000
,D/PMS     (  906): releaseWL(43a86160): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-01-17-48-33.bin
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(443773f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,D/PMS     (  906): acquireWL(43b596d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42337e18: PendingIntentRecord{422f4318 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1868371, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b596d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b59140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b59140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4454): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4807): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4807): ====startRecUseTime====
D/htc.customization.log.level( 4807):  is 
W/CustomizationLogLevel( 4807): Level value is invalid, use default level 2
D/CustomizationManager( 4807):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4807): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4807): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4807): Parsing tag category name = system
I/CustomizationCIDLoader( 4807): Parsing tag category name = application
I/CustomizationCIDLoader( 4807): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4807): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4807): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4807): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4807): Parsing tag category name = Settings
D/CustomizationManager( 4807):  Read CID file spent 0.157 (s)
D/CustomizationManager( 4807):  All configurations done spent 0.157 (s)
W/HtcNativeFlag( 4807): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4807): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4807): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4807): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4807, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4454
I/ActivityManager(  906): Killing 4454:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  906): killProcessQuiet, pid=4583
I/ActivityManager(  906): Killing 4583:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4566
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4552
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4566:com.android.chrome/u0a96 (adj 15): empty for 1803s
I/ActivityManager(  906): Killing 4552:com.google.android.setupwizard/u0a78 (adj 15): empty for 1803s
D/Process (  906): killProcessQuiet, pid=3945
I/ActivityManager(  906): Killing 3945:com.google.android.music:main/u0a154 (adj 15): empty for 1803s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4509
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4164
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4331
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4509:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
I/ActivityManager(  906): Killing 4164:com.android.vending/u0a73 (adj 15): empty for 1824s
I/ActivityManager(  906): Killing 4331:com.htc.cs.dm/u0a98 (adj 15): empty for 1836s
W/asset   (  906): Copying FileAsset 0x6471c6e0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906):   Force finishing activity ActivityRecord{42690ae0 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  906): Recipient 4509
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4331
I/ActivityManager(  906): Recipient 4566
I/ActivityManager(  906): Recipient 4164
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3945
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3945): Died!
I/ActivityManager(  906): Recipient 4583
I/ActivityManager(  906): Recipient 4552
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{4252bd28 com.example.hello/10355} due to missing metadata
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1207): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4454 uid 10348
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  906): WIN DEATH: Window{4274c558 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/dalvikvm-heap( 4201): Grow heap (frag case) to 15.215MB for 1821008-byte allocation
D/WifiService(  906): Client connection lost with reason: 4
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1580): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1580): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1912): Unregistering com.test.thalitest
E/acms    ( 1912): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1417): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  906): acquireWL(4273cb18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
D/PMS     (  906): releaseWL(4273cb18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/VoicemailCleanupService( 1294): Cleaning up data for package: com.test.thalitest
I/Launcher( 1267): Deferring update until onResume
D/Launcher( 1267): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
D/PackageBroadcastService( 1222): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
W/SystemReader( 1250): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4823 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1328): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  906): Delaying start of: ServiceRecord{4435c648 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 1222): CP2 sync disabled
W/Parcel  ( 1250): Reading a NULL string not supported here.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1222, uid=10028, userID:0
D/PMS     (  906): acquireWL(43d6f828): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
I/Icing   ( 1222): doRemovePackageData com.test.thalitest
I/MultiDex( 4823): install
I/MultiDex( 4823): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4823): loading existing secondary dex files
I/MultiDex( 4823): load found 1 secondary dex files
D/PMS     (  906): releaseWL(43d6f828): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4823): install done
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4840 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4823): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4840): install
I/MultiDex( 4840): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4840): loading existing secondary dex files
I/MultiDex( 4840): load found 1 secondary dex files
I/MultiDex( 4840): install done
I/ActivityManager(  906): Resuming delayed broadcast
I/ProviderInstaller( 4840): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1389): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1389): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4859 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 4201:com.google.android.apps.plus/u0a160 (adj 15): empty for 1804s
D/Process (  906): killProcessQuiet, pid=4201
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Recipient 4201
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4823): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4823): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4823): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4823): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4823): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4823): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4823): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4823): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4823): threadid=12: thread exiting with uncaught exception (group=0x419abe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4823): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4823): Process: com.google.android.gms.drive, PID: 4823
E/AndroidRuntime( 4823): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4823): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4823): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4823): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4823): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4823): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4823): 	at ctn.run(SourceFile:985)
D/Process ( 4823): killProcess, pid=4823
D/Process ( 4823): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4859, uid=10073, userID:0
D/Finsky  ( 4859): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4859/10073)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4859/10073)
I/ActivityManager(  906): Recipient 4823
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4823) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/TrimMemoryManager( 1267): [trimMemory] 5
D/Finsky  ( 4859): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  906): acquireWL(4251b368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
V/AlarmManager(  906): sending alarm PendingIntent{42e9c9c0: PendingIntentRecord{4282e458 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1910793, Int=0
W/Settings( 4859): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4859): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4859): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4859): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4859): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4859): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4859): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4859): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4859): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4859): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4859): threadid=25: thread exiting with uncaught exception (group=0x419abe30)
E/AndroidRuntime( 4859): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4859): Process: com.android.vending, PID: 4859
E/AndroidRuntime( 4859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4859): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4859): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4859): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4859): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4859): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4859): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4859): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.vending
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4859, uid=10073, userID:0
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
D/Prism.PackageStateRece_( 1267): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4859): killProcess, pid=4859
D/Process ( 4859): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2905): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4895 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
W/PackageManager(  906): Unable to load service info ResolveInfo{42781af0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  906): Recipient 4859
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.vending (pid 4859) has died.
E/SQLiteLog( 2905): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2905): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x635edc40
W/dalvikvm( 2905): threadid=15: thread exiting with uncaught exception (group=0x419abe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2905): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2905): Process: com.google.android.googlequicksearchbox:search, PID: 2905
E/AndroidRuntime( 2905): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2905): 	at cid.d(PG:186)
E/AndroidRuntime( 2905): 	at clo.g(PG:594)
E/AndroidRuntime( 2905): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2905): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2905): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2905): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2905): 	at clr.tL(PG:827)
E/AndroidRuntime( 2905): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2905): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2905): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2905): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2905): killProcess, pid=2905
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
D/Process ( 2905): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2905
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2905): Died!
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2905) has died.
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
E/SQLiteDatabase( 4895): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4895): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4895): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4895): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4895): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4895): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4895): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4895): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4895): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4895): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4895): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4895): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4895): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4895): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4895): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4895): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4895): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4895): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4895): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4895): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4895): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4895): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4895): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4895): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4895): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4895): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4895): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4895): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4895): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4895): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4895): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4895): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4895): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4895): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4895): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4895): Opened ClientFlag.db in read-only mode
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1267): loadItems() com.htc.launcher.pageview.WidgetManager@41e6ec90 +
I/Prism.WidgetManager( 1267): onLoadItems() +
E/SQLiteDatabase( 4895): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4895): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4895): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4895): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4895): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4895): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4895): threadid=11: thread exiting with uncaught exception (group=0x419abe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4895): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4895): Process: com.google.android.apps.docs, PID: 4895
E/AndroidRuntime( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4895): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4895): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4895): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4895): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4895): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
D/Process ( 4895): killProcess, pid=4895
D/Process ( 4895): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4911 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4895
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4895) has died.
W/ContextImpl( 4911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4911): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4911): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4911): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4911): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4911): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4911): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4911): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4911): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4911): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4911): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4911): threadid=10: thread exiting with uncaught exception (group=0x419abe30)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4924 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4911): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4911): Process: com.android.keychain, PID: 4911
E/AndroidRuntime( 4911): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4911): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4911): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4911): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4911): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4911): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4911): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4911): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4911): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4911): killProcess, pid=4911
D/Process ( 4911): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449064965027.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4911
I/ActivityManager(  906): Process com.android.keychain (pid 4911) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10429ms
D/AppTag  ( 4924): getInstance(Context context)
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start

```
