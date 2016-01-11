#### Test 5497026179923a9_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  905): Waited long enough for: ServiceRecord{446659c0 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4426): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4426): ====startRecUseTime====
D/htc.customization.log.level( 4426):  is 
W/CustomizationLogLevel( 4426): Level value is invalid, use default level 2
D/CustomizationManager( 4426):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4426): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4426): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4426): Parsing tag category name = system
I/CustomizationCIDLoader( 4426): Parsing tag category name = application
I/CustomizationCIDLoader( 4426): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4426): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4426): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4426): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4426): Parsing tag category name = Settings
D/CustomizationManager( 4426):  Read CID file spent 0.101 (s)
D/CustomizationManager( 4426):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 4426): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4426): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4426): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4426): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4426
D/PMS     (  905): acquireHCC(438d7d78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(438d7118): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x6510dcb0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1142334120
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d44298
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  905): acquireWL(438d1668): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4437 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4437): Copying FileAsset 0x5c73f428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4437): Binding Chromium to main looper Looper (main, tid 1) {41bf86a0}
I/LibraryLoader( 4437): Expected native library version number "",actual native library version number ""
I/chromium( 4437): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4437): Initializing chromium process, renderers=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42677180:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4437): 1103159512: getState(). Returning 12
D/PMS     (  905): acquireWL(43350ab0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(4273dd70): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(43350ab0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4437): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4437): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4437): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4437): Local Branch: 
I/Adreno-EGL( 4437): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4437): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4437):                  aa63bbd948f41d15fc72f585e
W/chromium( 4437): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4437): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4437): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4437): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4437): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4437): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4437): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4437): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4437): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4437): CordovaWebView is running on device made by: HTC
,W/AwContents( 4437): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1272
,I/InputMethodManagerService(  905): Enable input method client, pid=4437
W/ResourceType( 4437): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4437): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41c3f788, mServedView=org.apache.cordova.engine.SystemWebView{41c053f0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4437): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +269ms
,D/PMS     (  905): releaseWL(438d1668): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4437): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4437): JniHelper::setJavaVM(0x417b5010), pthread_self() = 1663167896
,D/JX-Cordova( 4437): jxcore cordova android initializing
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 11.557MB for 63974-byte allocation
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 11.590MB for 95956-byte allocation
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 11.661MB for 143930-byte allocation
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 11.776MB for 215890-byte allocation
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 11.951MB for 323830-byte allocation
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 12.626MB for 728606-byte allocation
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 13.223MB for 1092904-byte allocation
,D/PMS     (  905): acquireWL(4345eaf0): PARTIAL_WAKE_LOCK  Icing 0x1 2254 10028 null
,D/PMS     (  905): releaseWL(4345eaf0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(424a5ef0): PARTIAL_WAKE_LOCK  Icing 0x1 2254 10028 null
,D/PMS     (  905): releaseWL(424a5ef0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(4219b098): PARTIAL_WAKE_LOCK  Icing 0x1 2254 10028 null
,D/PMS     (  905): releaseWL(4219b098): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(424f5538): PARTIAL_WAKE_LOCK  Icing 0x1 2254 10028 null
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 14.108MB for 1639352-byte allocation
D/PMS     (  905): releaseWL(424f5538): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 15.449MB for 2459024-byte allocation
,I/dalvikvm-heap( 4437): Grow heap (frag case) to 17.464MB for 3688532-byte allocation
,W/jxcore-log( 4437): Initializing JXcore engine
,W/jxcore-log( 4437): JXcore engine is ready
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(438d7d78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(438d7118): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4437): Starting JXcore engine
,W/jxcore-log( 4437): Platform android
W/jxcore-log( 4437): 
,W/jxcore-log( 4437): Process ARCH arm
W/jxcore-log( 4437): 
,I/jxcore-log( 4437): JXcore Cordova bridge is ready!
I/jxcore-log( 4437): 
,W/jxcore-log( 4437): JXcore engine is started
,I/chromium( 4437): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4437): Toggling radios to true
I/jxcore-log( 4437): 
,D/BluetoothAdapter( 4437): enable(): BT is already enabled..!
,D/WifiManager( 4437): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 915
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
,W/Settings:Agent(  905): << traceCallingStack(): 2(ms)
D/WifiManager( 4437): disconnect: Base Package Name=com.test.thalitest, uid=10348,
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
,D/WifiManager( 4437): reconnect: Base Package Name=com.test.thalitest, uid=10348
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4437, uid=10348
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4437): Radios toggled
I/jxcore-log( 4437): 
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): TDLS: Tear down peers
I/wpa_supplicant( 1134): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4437): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4437): 
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1134): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1134): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1134): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1134): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1134): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1134): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1134): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1134): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7a26bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1134):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1134): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1134): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1134): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1134): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1134): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1134): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING (0),+
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1134): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1134): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1134): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  905): acquireWL(423f5f10): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): Power_Mode_Type mode = 0
I/wpa_supplicant( 1134): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): Fast associate: Old scan results
I/wpa_supplicant( 1134): wpa_supplicant_scan enter
I/wpa_supplicant( 1134): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1134): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1134): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  905):    returned true
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1134): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19170 mDataStallAlarmIntent=PendingIntent{442120d0: PendingIntentRecord{4267d6e0 android broadcastIntent}}
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): Power_Mode_Type mode = 0
I/wpa_supplicant( 1134): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1875/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
,D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/WifiNative-wlan0(  905):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WISPrService( 4213): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/WifiService(  905): New client listening to asynchronous messages
D/PMS     (  905): acquireWL(420eb278): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 4213): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:5   entry:0xb8c171c0  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8c176f0  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8c17818  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8c170e0  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8c17248  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb8c16d90  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb8c16fd8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8c17410  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  905): acquireWL(41ee94c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4213): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4213): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1875/10178)
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(4247fa80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1372/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/PMS     (  905): releaseWL(41ee94c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  905): releaseWL(420eb278): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiNative-wlan0(  905): doBoolean: SCAN
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1134): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
,D/PMS     (  905): releaseWL(4247fa80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
I/SensorManager(  905): mEventCount = 1350
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/PMS     (  905): releaseWL(4273dd70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4492 uid=10077 gids={50077}
,D/PMS     (  905): acquireWL(44111000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
V/AlarmManager(  905): sending alarm PendingIntent{42087d00: PendingIntentRecord{42108598 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452509435613, Int=60000
D/PMS     (  905): releaseWL(44111000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4492): SMSBackupAgentService started
,D/SMSBackup( 4492): Checking restore status
D/SMSBackup( 4492): Restore complete
,D/SMSBackup( 4492): cancelCheckAlarm
,D/SMSBackup( 4492): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=3643
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3643:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3643
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 3898): type=WIFI subType= reason=null isConnected=false
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  905): NoActiveNetworkState
,D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(43a40ce8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(43a40ce8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3898/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1444/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4324/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1875/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4324/10100)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2027/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4506 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4506): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4506): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4506): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4506): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4506): Preparing secondary program dexes.
V/DexLibLoader( 4506): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4506): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4506): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4506): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4506): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4506): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4506): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4506): Dex already copied
D/OdexVerifier( 4506): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4506): Creating class loader
,V/DexLibLoader( 4506): Finished creating class loader
V/DexLibLoader( 4506): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4506): Dex already copied
D/OdexVerifier( 4506): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4506): Creating class loader,
V/DexLibLoader( 4506): Finished creating class loader,
V/DexLibLoader( 4506): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4506): Dex already copied
D/OdexVerifier( 4506): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4506): Creating class loader
,V/DexLibLoader( 4506): Finished creating class loader
V/DexLibLoader( 4506): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4506): Dex already copied
D/OdexVerifier( 4506): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4506): Creating class loader,
V/DexLibLoader( 4506): Finished creating class loader
,V/DexLibLoader( 4506): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4506): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4506): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4506): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4506): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4506): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4506): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4506): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4506): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4506): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4506): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1134): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1134): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1134): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1134): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1134): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1134): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1134): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1134): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1134): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1134): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): Selecting BSS from priority group 1
I/wpa_supplicant( 1134): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1134): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1134): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1134): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1134):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1134):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 1134): Start print parameters
I/wpa_supplicant( 1134): wpa_s->wpa_state is 3
I/wpa_supplicant( 1134): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1134): isConcurrentMode() is 0
I/wpa_supplicant( 1134): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1134): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1134): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1134): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1134): wpa_s->reassociate is 1
I/wpa_supplicant( 1134): wpa_s->is_screen_on 1
I/wpa_supplicant( 1134): wpa_s->ifname wlan0
I/wpa_supplicant( 1134): End print parameters
I/wpa_supplicant( 1134): selected network = 1
D/wpa_supplicant( 1134): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7a284e8  current_ssid=0x0
D/wpa,_supplicant( 1134): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1134): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1134): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1134): check if in concurrent case
,I/wpa_supplicant( 1134): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1134): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1134): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1134): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1134): RSN: PMKSA cache search - network_ctx=0xb7a284e8 try_opportunistic=0
D/wpa_supplicant( 1134): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1134): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1134): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1134): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1134): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1134): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1134): nl80211: Unsubscribe mgmt frames handle 0xb7a27718 (mode change)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1134): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a27718
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb7a27718
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1134):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1134):   * freq=2412
D/wpa_supplicant( 1134):   * Auth Type 0
D/wpa_supplicant( 1134):   * WPA Versions 0x2
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1134): nl80211: Connect request send successfully
D/wpa_supplicant( 1134): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1134): reply (779) for get BSS: id=0
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1134): freq=5220
I/wpa_supplicant( 1134): level=-47,
I/wpa_supplicant( 1134): tsf=0000000105571386
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG7005g
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=1
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-53
I/wpa_supplicant( 1134): tsf=0000000105571409
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG700
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=2
I/wpa_supplicant( 1134): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1134): freq=2452
I/wpa_supplicant( 1134): level=-74
I/wpa_supplicant( 1134): tsf=0000000105571413
I/wpa_supplicant( 1134): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1134): ssid=Gonzos
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=3
I/wpa_supplicant( 1134): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-53
I/wpa_supplicant( 1134): tsf=0000000105571402
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1134): ssid=01ABC
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=4
I/wpa_supplicant( 1134): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1134): freq=2437
I/wpa_supplicant( 1134): level=-88
I/wpa_supplicant( 1134): tsf=0000000105571417
I/wpa_supplicant( 1134): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1134): ssid=UPC Wi-Free
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=5
I/wpa_supplicant( 1134): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1134): freq=2437
I/wpa_supplicant( 1134): level=-88
I/wpa_supplicant( 1134): tsf=0000000105571421
I/wpa_supplicant( 1134): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=UPC5999698
I/wpa_supplicant( 1134): ####
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 105571386, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 105571409, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2452, timestamp: 105571413, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 105571402, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 105571417, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 105571421, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,E/FbInjectorInitializer( 4506): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1134): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1134): nl80211: Connect event
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1134): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1134): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1134): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1134): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1134): Add randomness: count=12 entropy=6
I/wpa_supplicant( 1134): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1134): TDLS: Remove peers on association
D/wpa_supplicant( 1134): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1134): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1134): EAPOL: enable timer tick
D/wpa_supplicant( 1134): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1134): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1134): Get randomness: len=32 entropy=7
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..,
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1134): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7a279f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1134):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1134): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1134): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed4b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1134):    broadcast key
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1134): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1134): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1134): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1134): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700,
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1134): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1134): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): set send_ind_to_ndc = 0
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING (1)+,
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1134): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1134): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1134): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1134): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1134): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1134): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1134): EAPOL authentication completed successfully
I/wpa_supplicant( 1134): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,W/fb4a(:<default>):StaticBindingVerifier( 4506): Verify
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WISPrService( 4213): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4213): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): Power_Mode_Type mode = 1
I/wpa_supplicant( 1134): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(4334fcf8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424eaac8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424eaac8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4506): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4506): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=3214
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3214:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  905): acquireWL(44231178): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2254 10028 null
I/ActivityManager(  905): Recipient 3214
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42729b98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2254 10028 null
,D/PMS     (  905): releaseWL(44231178): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  905): releaseWL(42729b98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1415): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4535 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1415/10053)
,D/AutoSetting( 1415): Util - no network available!
,D/AutoSetting( 1415): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1415): service - mHandler: cancel location update
,D/AutoSetting( 1415): service -           changes count: 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1415/10053)
,W/fb4a(:<default>):UserScope( 4506): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4506): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4506): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4535): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4535): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4535): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4535): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4549 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4264
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4264:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4535/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4535/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4535/10078)
,I/ActivityManager(  905): Recipient 4264
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4506): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/WifiService(  905): Client connection lost with reason: 4
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4566 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3881
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  905): Killing 3881:com.htc.mediamanager/u0a32 (adj 15): empty #17
E/dalvikvm( 4506): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4506): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4506): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4506): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4506): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4506): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 9.964MB for 84664-byte allocation
,E/dalvikvm( 4506): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4506): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4506): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4566): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4566): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  905): Recipient 3881
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/GAV2    ( 4566): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 4566): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 9.975MB for 28144-byte allocation
E/dalvikvm( 4506): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4506): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4506): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/ContextImpl( 4566): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/dalvikvm( 4506): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4506): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4506): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4506): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4506): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4506): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 10.018MB for 39954-byte allocation
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 10.094MB for 79892-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4566/10151)
,V/WebViewChromiumFactoryProvider( 4566): Binding Chromium to main looper Looper (main, tid 1) {41bfd200}
,I/LibraryLoader( 4566): Expected native library version number "",actual native library version number ""
,I/chromium( 4566): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4566): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(43483058): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  905): acquireWL(434ffe98): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4566): BLUETOOTH permission is missing!
D/PMS     (  905): releaseWL(43483058): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4566): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4566): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4566): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4566): Local Branch: 
I/Adreno-EGL( 4566): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4566): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4566):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4566): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4566/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4566/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
,D/Process (  905): killProcessQuiet, pid=4294
,I/ActivityManager(  905): Killing 4294:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1875/10178)
I/ActivityManager(  905): Recipient 4294
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1875/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c91108 u0 ReceiverList{42c90fe8 4506 com.facebook.katana/10026/u0 remote:426cb1b0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c91108 u0 ReceiverList{42c90fe8 4506 com.facebook.katana/10026/u0 remote:426cb1b0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43a3a160 u0 ReceiverList{43a3a100 4506 com.facebook.katana/10026/u0 remote:43804f70}}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/PMS     (  905): acquireWL(43cd39d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
,D/PMS     (  905): releaseWL(43cd39d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1444): Unknown pending intent to remove.
D/PMS     (  905): acquireWL(436263a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
D/PMS     (  905): releaseWL(436263a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4506): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4506): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/wpa_supplicant( 1134): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1134): EAPOL: disable timer tick
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1134): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(4334fcf8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19172 delay=15s
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiWatchdogStateMachine(  905): WAN detection
,D/WISPrService( 4213): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1875/10178)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@425258d0
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(4368df38): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4535/10078)
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/PMS     (  905): acquireWL(4379ad50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2254 10028 null
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  905): acquireWL(43893db0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2254 10028 null
D/PMS     (  905): releaseWL(4379ad50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/CheckinService( 2254): Preparing to send checkin request
,I/EventLogService( 2254): Accumulating logs since 1452509386425
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,I/GoogleHttpClient( 2254): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2254): Using GMS GoogleHttpClient
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4368df38): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2254/10028)
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2254/10028)
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2254): awaiting user notification for token
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c55340 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 6 2 12
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4641 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4641): install
,I/MultiDex( 4641): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4641): loading existing secondary dex files
,I/MultiDex( 4641): load found 1 secondary dex files
,I/MultiDex( 4641): install done
,I/ProviderInstaller( 4641): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4641): Local Branch: 
I/Adreno-EGL( 4641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4641):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4641): Local Branch: 
I/Adreno-EGL( 4641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4641):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1117): WifiActivity: 2
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  905): releaseWL(423f5f10): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(44346f18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3898/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4324/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1444/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1875/10178)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3920/10051)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4535/10078)
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
I/acms    ( 1905): Checking Certificates
,I/acms    ( 1905): Checking Developer Certificates
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 3898): type=WIFI subType= reason=null isConnected=true
I/acms    ( 1905): Checking Application Certificates
I/acms    ( 1905): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1905): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1905): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1905): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1905): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1905): Updating next query delay: 75600000
I/mlserverapp( 1905): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1905): cancelACMSProgrammedChecks
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4324/10100)
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
D/PMS     (  905): acquireWL(44182188): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(44182188): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(44346f18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2027/10021)
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(4333f378): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2254 10028 null
D/PMS     (  905): releaseWL(4333f378): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028),
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    ( 1372): [NET] getaddrinfo-, 1
,D/libc    ( 1372): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =939b +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  905): acquireWL(42477d68): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,D/AutoSetting( 1415): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4535): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4535): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1415): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1415/10053)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4566/10151)
D/AutoSetting( 1415): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1415): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1415): service - onStartCommand() REMOVE current location bundle
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1415): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1415): service - onStartCommand() check timezone in 30000
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1415/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4190/10160)
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1415): service - handleMessage() setting current location null
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1875/10178)
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 13.516MB for 1821008-byte allocation
,I/Adreno-EGL( 4641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4641): Local Branch: 
I/Adreno-EGL( 4641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4641):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  905): acquireWL(441df878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  905): releaseWL(441df878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4641/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,W/fb4a(:<default>):UserScope( 4506): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4506): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [6][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-53 , oldRssi= -200
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/GCM     ( 1372): Connected
,W/Settings( 4641): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PMS     (  905): acquireWL(4262fb68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  905): releaseWL(42477d68): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  905): releaseWL(4262fb68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(424e9a50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
,I/CheckinTask( 2254): Sending checkin request (9157 bytes)
,D/GCM     ( 1372): Message class mpf
,D/libc    ( 2254): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/libc    ( 2254): [NET] getaddrinfo-,err=8
D/libc    ( 2254): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2254): [NET] getaddrinfo-, 1
D/libc    ( 2254): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7b0d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  905): releaseWL(424e9a50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(43f309b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  905): releaseWL(43f309b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 255
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2254): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2254): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2254): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4506): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [17][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(425a8920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  905): releaseWL(425a8920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2254/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2254/10028)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [1][0][0]
,D/PMS     (  905): releaseWL(434ffe98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2254): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c79c68 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 6 3 12
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/CheckinTask( 2254): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2254): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  905): releaseWL(43893db0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2254): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e77e20 that was originally bound here
E/ActivityThread( 2254): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e77e20 that was originally bound here
E/ActivityThread( 2254): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2254): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2254): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2254): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2254): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2254): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2254): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2254): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2254): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2254): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2254): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2254): 	at bks.a(SourceFile:298)
E/ActivityThread( 2254): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2254): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2254): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2254): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1372): GCM config loaded
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42270cd8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42270cd8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424130f0
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@41e789b0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,W/PMS     (  905): mWirelessDisplayManager is null
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 370ms
D/NfcService( 1250): ScreenObserver: OFF
D/NfcService( 1250): applyRouting - 0
,D/NfcService( 1250): applyRouting -2
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
D/PMS     (  905): OOBE c monitor 11
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4437
D/PMS     (  905): acquireWL(4416ebb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1250 1027 null
,D/PMS     (  905): releaseWL(4416ebb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@439a2e30)
D/PMN     (  905): wakingUp
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  905): No lock screen! windowToken=null
D/PMN     (  905): onScreenOn
,D/PMS     (  905): acquireWL(4413acc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done recovering
D/PMS     (  905): releaseWL(4413acc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 2027): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2027): [MTP][onReceive]-
,D/NfcService( 1250): applyRouting - 0
D/NfcService( 1250): applyRouting -2
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): acquireWL(442286c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1250 1027 null
D/PMS     (  905): releaseWL(442286c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19173 delay=15s
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/ClockThread( 1117): stop update clock
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4682 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): SET_SCREEN_ON:On
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING - ret = 0
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus,
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d9b +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/ContextImpl( 4682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  905): updateScreenOn: false
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [1][0][0]
,D/SmartSyncUtils( 4682): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(43868088): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4682 1000 null
,D/SmartSyncUtils( 4682): getMobilePolicyEnabled, result = true
D/PMS     (  905): releaseWL(43868088): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  905): killProcessQuiet, pid=4324
,I/ActivityManager(  905): Killing 4324:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1415): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1415): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43cc5000): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1444 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1850): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): onScreenOn: 1452509442247
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1850): onScreenOn: 1452509442247
D/TetherSettings( 4213): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4213): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4213): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4213): Cust_ConnectToPC   : spcsc>false
D/        ( 4213): Cust_ConnectToPC   : IPT>true
,D/        ( 4213): Cust_ConnectToPC   : Singel_USB>false
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424130f0
,W/Settings( 4213): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  905): releaseWL(43cc5000): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
E/SmartNS_Utility( 4213): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4213): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4213): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424130f0, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@41e789b0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/PSReceiver( 4213): onReceive:android.intent.action.USER_PRESENT
D/PMN     (  905): goingToSleep
W/ContextImpl( 4213): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): acquireWL(4422af68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,I/SmartNS_PSService( 4213): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4213): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4213):  defaultType:0
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19173 mDataStallAlarmIntent=PendingIntent{43323c78: PendingIntentRecord{4267d6e0 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): SET_SCREEN_ON:Off
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1134): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
,D/PMS     (  905): acquireWL(42caac70): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/NetworkPolicy(  905): updateScreenOn: false
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/ContactMessageStore( 1239): start background delete task...
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Recipient 4324
D/PMS     (  905): releaseWL(42caac70): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
W/ContextImpl( 4682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4682): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4682): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4682): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41e789b0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41e789b0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41e789b0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41e789b0
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424c0f88 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424c0f88 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1415): service - mHandler: cancel location update
D/AutoSetting( 1415): service -           changes count: 0
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1850): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1850): onScreenOff
D/PMS     (  905): acquireWL(44172218): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1444 10028 null
D/PMS     (  905): releaseWL(44172218): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{42129428 u0 com.test.thalitest/.MainActivity t2}
,I/GAV2    ( 4566): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  905): acquireWL(43670230): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
,D/PMS     (  905): acquireWL(43766e88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
,D/PMS     (  905): releaseWL(43670230): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): releaseWL(43766e88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/jxcore-log( 4437): Test app app.js loaded
I/jxcore-log( 4437): 
,I/Choreographer( 4437): Skipped 537 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4437): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4437): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41c053f0 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4437): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  905): releaseWL(4422af68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  905): killProcessQuiet, pid=4349
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4349:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4349
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1522): service - handleMessage() stop self
,D/AutoSetting( 1522): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=4366
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1522): service - handleMessage() quit looper
I/ActivityManager(  905): Killing 4366:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4366
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 11.000MB for 51986-byte allocation
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 11.005MB for 43014-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 11.053MB for 65542-byte allocation
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 11.060MB for 44254-byte allocation
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 11.092MB for 57404-byte allocation
,D/libc    ( 4506): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4506): [NET] getaddrinfo-,err=8
D/libc    ( 4506): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4506): [NET] getaddrinfo-, 1
,D/libc    ( 4506): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ca8c +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 4
D/libc    (  365): [NET]res_nsend:resplen=93
D/libc    (  365): [NET]res_queryN: exit 3, ancount=3
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4506): [NET] getaddrinfo_proxy-, success
I/global  ( 4506): call createSocket() return a new socket.
D/libc    ( 4506): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4506): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4506): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4506): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(43998830): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4506 10026 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 11.180MB for 66236-byte allocation
,I/dalvikvm-heap( 4506): Grow heap (frag case) to 11.211MB for 85942-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4506/10026)
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4506): I/O error closing connection
I/global  ( 4506): java.net.SocketException: Socket is closed
I/global  ( 4506): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4506): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4506): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4506): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4506): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4506): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4506): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4506): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4506): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4506): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4506): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4506): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4506): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4506): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4506): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4506): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4506): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4506): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4506): Removing a connection that never existed!
D/PMS     (  905): releaseWL(43998830): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(43728fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=128305, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43728fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43a17d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  905): releaseWL(43a17d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1415): service - mHandler: update timezone
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1522): service - onCreate()
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1616): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
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
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c86910 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 1415): service - handleMessage() stop self
,D/PMS     (  905): acquireWL(44394468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028}
,V/AlarmManager(  905): sending alarm PendingIntent{43cd0308: PendingIntentRecord{425642c8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140685, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42488760: PendingIntentRecord{424b9c68 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140807, Int=0
,D/AutoSetting( 1415): service - onDestroy() END
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  905): acquireWL(4362c740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/AutoSetting( 1415): service - handleMessage() quit looper
D/PMS     (  905): acquireWL(4386a5b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(44394468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  905): releaseWL(4362c740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9de +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 16
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(4386a5b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  905): killProcessQuiet, pid=3920
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3920:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3920
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43d88ce0 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1522): service - handleMessage() stop self
,D/AutoSetting( 1522): service - onDestroy() END
,D/AutoSetting( 1522): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4311
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4311:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4311
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(439986a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(439986a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(44667f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=188305, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44667f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(445d9288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(445d9288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(442bdda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{423c5b60: PendingIntentRecord{438bda40 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226463, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4727 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{42652110: PendingIntentRecord{424ed308 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452509551746, Int=10800000
,D/PMS     (  905): releaseWL(442bdda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4727/10047)
,D/Process (  905): killProcessQuiet, pid=4384
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4384:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4384
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,D/PMS     (  905): acquireWL(441f5e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(441f5e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,D/PMS     (  905): acquireWL(441b2690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{441e05e0: PendingIntentRecord{438bda40 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230592, Int=0
,D/PMS     (  905): releaseWL(441b2690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(44128ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=248304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44128ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4411bd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(4411bd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(438e6fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(438e6fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(438c9320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=308304, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(438c9320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(438be7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(438be7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4437): TAP version 13
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # multiplex can send data,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 1 String should be length:200
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # basic,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 2 sane
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # another
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 3 sane
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # successfully create a new pkcs12 file and return hash value,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 4 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 5 null,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 6 (unnamed assert)
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 7 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 8 should not throw
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 9 (unnamed assert)
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 10 (unnamed assert)
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 11 should not throw
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 12 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 13 should be equal,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # failed to extract public key because of corrupt pkcs12 file,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 14 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # failed to get mobile documents path
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 15 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 16 should be equal,
I/jxcore-log( 4437): 
I/jxcore-log( 4437): ok 17 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 18 should be equal,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #init should register the networkChanged event
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 19 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #startBroadcasting should throw on null device name
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 20 should throw,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #startBroadcasting should throw on empty string device name,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 21 should throw,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #startBroadcasting should throw on non-number port,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 22 should throw,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #startBroadcasting should throw on NaN port,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 23 should throw,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #startBroadcasting should throw on negative port
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 24 should throw
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #startBroadcasting should throw on too large port
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 25 should throw
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 26 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 27 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 28 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 29 should be equal
I/jxcore-log( 4437): 
I/jxcore-log( 4437): ok 30 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 31 should be equal,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 32 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 33 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 34 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 35 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #connect should call Mobile("Connect") with a port and without an error,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 36 should be equal,
I/jxcore-log( 4437): 
I/jxcore-log( 4437): ok 37 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 38 should be equal,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4437): ,
,I/jxcore-log( 4437): # teardown,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 39 should be equal,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 40 should be equal,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 41 should be equal,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 42 should be equal
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 43 should be equal,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): ok 44 should be equal,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # setup
I/jxcore-log( 4437): ,
,I/jxcore-log( 4437): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error,
I/jxcore-log( 4437): 
,I/jxcore-log( 4437): # teardown,
I/jxcore-log( 4437): 
,W/dalvikvm( 4437): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4437): threadid=1: thread exiting with uncaught exception (group=0x417c6e30)
E/AndroidRuntime( 4437): FATAL EXCEPTION: main
E/AndroidRuntime( 4437): Process: com.test.thalitest, PID: 4437
E/AndroidRuntime( 4437): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4437): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4437): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4437): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4437): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4437): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 4437): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/AndroidRuntime( 4437): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4437): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4437): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4437): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4437): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4437): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4437): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4437): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4437): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4437): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4437): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4437): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  905): App crashed! Process: com.test.thalitest
W/ActivityManager(  905):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  905): killProcessQuiet, pid=4398
,I/ActivityManager(  905): Killing 4398:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,D/Process ( 4437): killProcess, pid=4437
,D/Process ( 4437): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,W/InputDispatcher(  905): channel '42588a40 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '42588a40 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '42588a40 com.test.thalitest.MainActivity (s)'
I/ActivityManager(  905): Recipient 4437
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.test.thalitest (pid 4437) has died.
D/WifiService(  905): Client connection lost with reason: 4
I/WindowManager(  905): WINDOW DIED Window{42588a40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/WindowManager(  905): Failed looking up window
W/WindowManager(  905): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@420e2858 does not exist
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  905): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  905): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  905): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  905): WIN DEATH: null
,I/ActivityManager(  905): Recipient 4398
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4437 uid 10348
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(43310518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43310518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1616): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,E/PlayEventLogger( 4155): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4155): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4155): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4155): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4155): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4155): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4155): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4155): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41fb5f28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 8 3 12
,D/libc    ( 4155): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4155): [NET] getaddrinfo-,err=8
D/libc    ( 4155): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4155): [NET] getaddrinfo-, 1
,D/libc    ( 4155): [NET] getaddrinfo_proxy+,
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =692a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 16
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4155): [NET] getaddrinfo_proxy-, success
I/global  ( 4155): call createSocket() return a new socket.
D/libc    ( 4155): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4155): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4155): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4155): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(41e126c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=368304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(41e126c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427293d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(427293d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42608090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{43c3d190: PendingIntentRecord{43cc1d28 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=410231, Int=300000
,V/AlarmManager(  905): sending alarm PendingIntent{443ff758: PendingIntentRecord{438857f0 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1452509689474, Int=0
,D/PMS     (  905): releaseWL(42608090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 2254): No account for auth token provided
,D/libc    ( 2254): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2254): [NET] getaddrinfo-,err=8
D/libc    ( 2254): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2254): [NET] getaddrinfo-, 1
,D/libc    ( 2254): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5bef +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2254): [NET] getaddrinfo_proxy-, success
I/global  ( 2254): call createSocket() return a new socket.
D/libc    ( 2254): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2254): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2254): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2254): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,D/PMS     (  905): acquireWL(424eadb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1642): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/DotMatrix( 1616): [EventService] reorderNotification, total:1
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1117): closing low battery warning: level=98
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(424eadb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/ContextImpl( 4682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 ,
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
D/TetherSettings( 4213): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4213): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4213): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4213): Cust_ConnectToPC   : spcsc>false
D/        ( 4213): Cust_ConnectToPC   : IPT>true
,D/        ( 4213): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4213): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4213): Index of the first 1 = -1
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
W/ContextImpl( 4213): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4213): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4213): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4213): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4213): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4213): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 4213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42465480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=428304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42465480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43868108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  905): releaseWL(43868108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=98
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(426dfc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): releaseWL(426dfc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=98
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4264ce10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=488304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4264ce10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43355528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43355528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(425d0090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=548304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425d0090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(424e6c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(424e6c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42069418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): releaseWL(42069418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=98
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4262c5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=608304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4262c5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42606b10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10073}
,V/AlarmManager(  905): sending alarm PendingIntent{42b0e740: PendingIntentRecord{4218ebe0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452509942181, Int=0
,D/PMS     (  905): releaseWL(42606b10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4155): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4155): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4155): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4155): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4155): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/PMS     (  905): acquireWL(43d6fdf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43d6fdf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1239): sku_id=99
D/ContactMessageStore( 1239): start background delete task...
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/PMS     (  905): acquireWL(44322798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10073}
,V/AlarmManager(  905): sending alarm PendingIntent{4255f7c0: PendingIntentRecord{43a86908 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452509957366, Int=0
,D/PMS     (  905): releaseWL(44322798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4155): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  905): acquireWL(438dd848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(438dd848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=99
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43da45e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=668304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43da45e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43306138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43306138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(438c9250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(438c9250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=99
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43d979f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{43c3d190: PendingIntentRecord{43cc1d28 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=710231, Int=300000
,D/PMS     (  905): releaseWL(43d979f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(440d09e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=728304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(440d09e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41bf5f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41bf5f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43932db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41ec8868: PendingIntentRecord{42530088 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785565, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{4244e3e0: PendingIntentRecord{425e56f8 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1452510000000, Int=86400000
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): releaseWL(43932db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
,D/PMS     (  905): acquireWL(43dca4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=788304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43dca4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(441e28a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  905): releaseWL(441e28a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=99
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43679140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43679140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1616): [EventService] reorderNotification, total:0
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1642): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/ContextImpl( 4682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4213): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4213): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4213): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4213): Cust_ConnectToPC   : spcsc>false
,D/        ( 4213): Cust_ConnectToPC   : IPT>true
,D/        ( 4213): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4213): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4213): Index of the first 1 = -1
W/Settings( 4213): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4213): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4213): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4213): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4213): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/ContextImpl( 4213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43dba820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=848304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43dba820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4267e320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4267e320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(438be428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=908304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(438be428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43662d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43662d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43d1d000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=968304, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43d1d000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42c9e748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42c9e748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43aacc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028}
,V/AlarmManager(  905): sending alarm PendingIntent{4243c9b0: PendingIntentRecord{4274f118 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1008833, Int=0
,D/PMS     (  905): acquireWL(44125998): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1372 10028 null
,V/AlarmManager(  905): sending alarm PendingIntent{425bf800: PendingIntentRecord{42689728 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452510272131, Int=900000
,V/AlarmManager(  905): sending alarm PendingIntent{436e43c8: PendingIntentRecord{426771f0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452510315969, Int=1800000
,D/PMS     (  905): releaseWL(44125998): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,V/AlarmManager(  905): sending alarm PendingIntent{42728e80: PendingIntentRecord{44268df8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452510342329, Int=0
,W/ContextImpl( 4682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): acquireWL(437a2b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  905): releaseWL(437a2b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4682): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4682): MY_DEBUG = false
D/PMS     (  905): acquireWL(44211ac8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2254 10028 null
,D/SmartSyncUtils( 4682): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(44270618): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2254 10028 null
D/PMS     (  905): releaseWL(44211ac8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/PMS     (  905): releaseWL(43aacc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/EventLogService( 2254): Aggregate from 1452509439162 (log), 1452508515800 (data)
D/PMS     (  905): acquireWL(441e91a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4682 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4682): [updateNmRange] bManual = false
,W/BatSI   (  905): Couldn't get kernel wake lock stats
D/SmartSyncScreenOnOffTimeReceiver( 4682): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 20, nEnd = 23, bNormalRange = true
,D/PMS     (  905): releaseWL(44270618): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/SmartSyncScreenOnOffTimeReceiver( 4682): [updateNmRange] new USERNIGHT_TIMESTART = 20, new USERNIGHT_TIMEEND = 23
,I/FeedHostManager( 1272): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,D/SmartSyncScreenOnOffTimeReceiver( 4682): AlarmOnTime = -1
,I/FeedHostManager( 1272): NightMode begin at 0, end at 7
W/ContextImpl( 4682): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,D/PMS     (  905): acquireWL(426d1de0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1272 10075 null
D/SmartSyncScreenOnOffTimeReceiver( 4682): SettingOnTime = 1452549600000, randomSettingOnTime = 1452548880000
D/SmartSyncScreenOnOffTimeReceiver( 4682): SettingOffTime = 1452538800000, randomSettingOffTime = 1452541474000
,D/SmartSyncScreenOnOffTimeReceiver( 4682): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4682): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4682): bNightModeTurnOffOnce = false
,I/FeedHostManager( 1272): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1452510342505, BeginTime: 1452553200000, EndTime: 1452578400000
D/PMS     (  905): releaseWL(441e91a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  905): releaseWL(426d1de0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(441d8f60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
,D/GCM     ( 1372): Message class mow
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  905): acquireWL(4417da50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  905): releaseWL(441d8f60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  905): releaseWL(4417da50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=6 [345][22][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(44100780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1028304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44100780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43dc1700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43dc1700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43ccaea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1088304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43ccaea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43b49b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b49b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(439d7650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(439d7650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4381cf18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1148304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4381cf18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4377e7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4377e7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(436ef3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1208304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(436ef3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43644148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43644148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(434e83c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1268304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(434e83c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(433c35e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(433c35e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4331de80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1328305, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4331de80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42cbcd68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42cbcd68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4278c380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1388304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4278c380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4271abd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4271abd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(426d83b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1448304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(426d83b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42696068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42696068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42650808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1508304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42650808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425ca958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425ca958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(425448e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1568305, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425448e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(424bca00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(424bca00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42467410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1628305, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42467410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42164008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42164008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(41ed7730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1688304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(41ed7730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41bedc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41bedc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(425b9528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1748304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425b9528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4252c360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4252c360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(41dbff38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1808304, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(41dbff38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43c248f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c248f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(42484dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41ec8868: PendingIntentRecord{42530088 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505593, Int=0
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,I/ProcessStatsService(  905): Prepared write state in 35ms
,I/ProcessStatsService(  905): Prepared write state in 20ms
,V/AlarmManager(  905): sending alarm PendingIntent{42489f10: PendingIntentRecord{425f9e80 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820337, Int=1800000
,D/PMS     (  905): acquireWL(424694d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,V/AlarmManager(  905): sending alarm PendingIntent{425bf800: PendingIntentRecord{42689728 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452511172131, Int=900000
,D/PMS     (  905): releaseWL(424694d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ProcessStatsService(  905): Pruning old procstats: /data/system/procstats/state-2016-01-10-09-34-37.bin
,W/ContextImpl( 4682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(42484dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(441099d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f6be90: PendingIntentRecord{41f0ddf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1868305, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(441099d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(438f74b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(438f74b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43cfed30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1616): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1616): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
D/PMS     (  905): releaseWL(43cfed30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  905): >> updateStatus
,D/Process (  905): killProcessQuiet, pid=4042
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  905): Killing 4042:com.google.android.gm/u0a107 (adj 15): empty for 1816s
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  905): Recipient 4042
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4795): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4795): ====startRecUseTime====
D/htc.customization.log.level( 4795):  is 
W/CustomizationLogLevel( 4795): Level value is invalid, use default level 2
D/CustomizationManager( 4795):  Read ACC file spent 0.123 (s)
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4795): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4795): Parsing tag category name = system
I/CustomizationCIDLoader( 4795): Parsing tag category name = application
I/CustomizationCIDLoader( 4795): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4795): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4795): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4795): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4795): Parsing tag category name = Settings
D/CustomizationManager( 4795):  Read CID file spent 0.180 (s)
D/CustomizationManager( 4795):  All configurations done spent 0.180 (s)
W/HtcNativeFlag( 4795): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4795): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4795): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4795): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4795, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=4190
I/ActivityManager(  905): Killing 4190:com.google.android.apps.plus/u0a160 (adj 15): empty for 1802s
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=4566
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=4549
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=4535
I/ActivityManager(  905): Killing 4566:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  905): Killing 4549:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  905): Killing 4535:com.google.android.setupwizard/u0a78 (adj 15): empty for 1802s
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=3898
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=4492
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  905): Killing 3898:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
I/ActivityManager(  905): Killing 4492:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  905): Copying FileAsset 0x678d5588 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  905): Recipient 4492
I/ActivityManager(  905): Recipient 3898
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4535
D/MediaRouterService(  905): Client com.google.android.music (pid 3898): Died!
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4190
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4566
W/PackageSettings(  905): Skipping PackageSetting{422eb740 com.example.hello/10356} due to missing metadata
I/ActivityManager(  905): Recipient 4549
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/acms    ( 1905): Unregistering com.test.thalitest
E/acms    ( 1905): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1616): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1616): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1616): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  905): acquireWL(438d7d78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1444 10028 null
W/GeofencerStateMachine( 1444): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(438d7d78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Launcher( 1272): Deferring update until onResume
D/Launcher( 1272): waitUntilResume // bindAppsRemoved
W/SystemReader( 1250): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1284): Cleaning up data for package: com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PackageBroadcastService( 2254): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4810 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
E/ExternalAccountType( 1323): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/MultiDex( 4810): install
I/ActivityManager(  905): Delaying start of: ServiceRecord{443a3a00 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/MultiDex( 4810): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/MultiDex( 4810): loading existing secondary dex files
I/MultiDex( 4810): load found 1 secondary dex files
I/MultiDex( 4810): install done
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4826 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2254): CP2 sync disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2254, uid=10028, userID:0
D/PMS     (  905): acquireWL(425107e8): PARTIAL_WAKE_LOCK  Icing 0x1 2254 10028 null
I/Icing   ( 2254): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4810): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PMS     (  905): releaseWL(425107e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4826): install
I/MultiDex( 4826): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4826): loading existing secondary dex files
I/MultiDex( 4826): load found 1 secondary dex files
I/MultiDex( 4826): install done
I/ProviderInstaller( 4826): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/SQLiteDatabase( 2254): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2254): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2254): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2254): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2254): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2254): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2254): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2254): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2254): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2254): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2254): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2254): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2254): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2254): Runtime exception while performing operation
E/ClearPendingStateOp( 2254): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2254): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2254): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2254): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2254): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2254): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2254): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2254): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2254): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2254): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2254): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2254): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2254): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2254): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2254): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2254): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2254): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2254): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2254): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2254): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2254): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2254): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2254): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2254): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2254): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Resuming delayed broadcast
E/SharedPreferencesImpl( 1208): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1415): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/DropBoxManagerService(  905): Can't write: system_app_wtf
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
E/SQLiteLog( 1415): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1415): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9d7838
W/[PluginManager]RegisterService( 1415): provider may killed!
W/[PluginManager]RegisterService( 1415): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1415): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1415): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1415): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1415): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1415): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1415): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1415): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1415): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1415): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2899): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4850 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2899): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2899): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca3d1e0
W/dalvikvm( 2899): threadid=14: thread exiting with uncaught exception (group=0x417c6e30)
E/AndroidRuntime( 2899): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2899): Process: com.google.android.googlequicksearchbox:search, PID: 2899
E/AndroidRuntime( 2899): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2899): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2899): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2899): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2899): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2899): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2899): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2899): 	at cid.d(PG:186)
E/AndroidRuntime( 2899): 	at clo.g(PG:594)
E/AndroidRuntime( 2899): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2899): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2899): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2899): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2899): 	at clr.tL(PG:827)
E/AndroidRuntime( 2899): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2899): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2899): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2899): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2899): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
E/SQLiteDatabase( 4810): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4810): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4810): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4810): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4810): threadid=12: thread exiting with uncaught exception (group=0x417c6e30)
D/Process ( 2899): killProcess, pid=2899
E/AndroidRuntime( 4810): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4810): Process: com.google.android.gms.drive, PID: 4810
E/AndroidRuntime( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4810): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4810): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4810): 	at ctn.run(SourceFile:985)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
D/Process ( 4810): killProcess, pid=4810
D/Process ( 2899): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
D/Process ( 4810): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
I/ActivityManager(  905): Recipient 2899
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2899) has died.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2899): Died!
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4810
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/WifiService(  905): Client connection lost with reason: 4
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4810) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10989ms
W/PackageManager(  905): Unable to load service info ResolveInfo{4268cf40 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4850): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4850): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4850): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4850): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4850): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4850): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4850): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4850): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4850): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4850): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4850): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4850): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4850): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4850): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4850): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4850): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4850): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4850): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4850): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4850): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4850): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4850): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4850): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4850): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4850): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4850): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4850): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4850): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4850): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4850): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4850): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4850): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4850): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4850): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4850): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4850): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4850): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4850): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4850): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4850): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4850): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4850): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4850): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4850): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4850): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4850): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4850): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4850): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4850): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4850): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4850): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4850): threadid=11: thread exiting with uncaught exception (group=0x417c6e30)
E/AndroidRuntime( 4850): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4850): Process: com.google.android.apps.docs, PID: 4850
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
E/AndroidRuntime( 4850): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4850): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4850): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4850): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4850): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
D/Process ( 4850): killProcess, pid=4850
D/Process ( 4850): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4868 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Recipient 4850
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4850) has died.
W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
E/SQLiteDatabase( 4868): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4868): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4868): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4868): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4868): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4868): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4868): threadid=10: thread exiting with uncaught exception (group=0x417c6e30)
E/AndroidRuntime( 4868): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4868): Process: com.android.keychain, PID: 4868
E/AndroidRuntime( 4868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4868): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4868): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4868): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4868): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4868): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4881 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/Process ( 4868): killProcess, pid=4868
D/Process ( 4868): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452511244665.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Recipient 4868
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4868) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10567ms
D/AppTag  ( 4881): getInstance(Context context)
D/AppTag  ( 4881): getInstance(Context context)
D/AppTag  ( 4881): onCreate()
I/ActivityManager(  905): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4896 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/PMS     (  905): acquireWL(43324c50): PARTIAL_WAKE_LOCK  AsyncService 0x1 4896 10160 null
D/PMS     (  905): releaseWL(43324c50): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4916 uid=10098 gids={50098, 3003, 5012}
E/SQLiteDatabase( 4896): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4896): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4896): 	at del.a(PG:264)
E/SQLiteDatabase( 4896): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4896): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 4896): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4896): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4896): 	at del.a(PG:264)
E/SQLiteDatabase( 4896): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4896): 	at java.lang.Thread.run(Thread.java:864)
E/EsApplication( 4896): Failed app initialization
E/EsApplication( 4896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4896): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4896): 	at del.a(PG:264)
E/EsApplication( 4896): 	at eeq.run(PG:187)
E/EsApplication( 4896): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4916): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4916 dbg=false s=true
I/DeviceManagement( 4916): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4916): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4916): WorkflowService: Starting workflow service
I/DeviceManagement( 4916): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c2b2d8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4916): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4916): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4916): PackageUpdateWorkflow: ==================================================
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4930 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4916): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 4916): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4916): SessionStateController: Checking invariants...
D/Documents( 4930): Loading roots for com.android.providers.downloads.documents
,E/SQLiteDatabase( 4930): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
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
E/SQLiteDatabase( 4930): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4930): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4930): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4930): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4930): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4930): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4930): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4930): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4930): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4930): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4930): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4930): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4930): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4930): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4930): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4930): 	at dalvik.system.NativeStart.main(Native Method)

```
