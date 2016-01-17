#### Test 56151093914d164_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  905): mEventCount = 1050
,E/cutils-trace( 4374): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4374): ====startRecUseTime====
D/htc.customization.log.level( 4374):  is 
W/CustomizationLogLevel( 4374): Level value is invalid, use default level 2
D/CustomizationManager( 4374):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4374): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4374): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4374): Parsing tag category name = system
I/CustomizationCIDLoader( 4374): Parsing tag category name = application
I/CustomizationCIDLoader( 4374): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4374): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4374): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4374): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4374): Parsing tag category name = Settings
D/CustomizationManager( 4374):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4374):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 4374): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4374): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4374): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4374): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4374
D/PMS     (  905): acquireHCC(4386f540): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(43855150): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x69bcbe48 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1138296768
D/PMS     (  905): acquireWL(43819568): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c84050
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4385 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4385): Copying FileAsset 0x5c851428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4385): Binding Chromium to main looper Looper (main, tid 1) {41b08388}
I/LibraryLoader( 4385): Expected native library version number "",actual native library version number ""
I/chromium( 4385): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4385): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(43732758): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(4372bb78): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(4372bb78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@437250d0:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4385): 1102175680: getState(). Returning 12
,I/Adreno-EGL( 4385): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4385): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4385): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4385): Local Branch: 
I/Adreno-EGL( 4385): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4385): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4385):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4385): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4385): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4385): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4385): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4385): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4385): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 4385): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4385): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4385): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4385): CordovaWebView is running on device made by: HTC
,W/AwContents( 4385): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1273
,W/ResourceType( 4385): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4385): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b4f470, mServedView=org.apache.cordova.engine.SystemWebView{41b150d8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Enable input method client, pid=4385
,W/AwContents( 4385): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +424ms
,D/PMS     (  905): releaseWL(43819568): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4385): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4385): JniHelper::setJavaVM(0x415d7048), pthread_self() = 1663122008
,D/JX-Cordova( 4385): jxcore cordova android initializing
,I/dalvikvm-heap( 4385): Grow heap (frag case) to 12.044MB for 63974-byte allocation
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/dalvikvm-heap( 4385): Grow heap (frag case) to 12.095MB for 95956-byte allocation
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/dalvikvm-heap( 4385): Grow heap (frag case) to 12.158MB for 143930-byte allocation
,I/dalvikvm-heap( 4385): Grow heap (frag case) to 12.273MB for 215890-byte allocation
,I/dalvikvm-heap( 4385): Grow heap (frag case) to 12.448MB for 323830-byte allocation
,I/dalvikvm-heap( 4385): Grow heap (frag case) to 13.123MB for 728606-byte allocation
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=159 rxSum=153} preTxRxSum={txSum=159 rxSum=153}
D/WifiDataStallTracker(  905): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=21038 Sent 0 pkts since last received, < watchdogTrigger=5
D/PMS     (  905): acquireWL(4389e048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{43b6fc18: PendingIntentRecord{41c2a0f8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103177, Int=0
,D/PMS     (  905): releaseWL(4389e048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  905): startDataStallAlarm: tag=21039 delay=15s
,I/dalvikvm-heap( 4385): Grow heap (frag case) to 13.720MB for 1092904-byte allocation
,I/dalvikvm-heap( 4385): Grow heap (frag case) to 14.640MB for 1639352-byte allocation
,I/dalvikvm-heap( 4385): Grow heap (frag case) to 15.884MB for 2459024-byte allocation
,I/dalvikvm-heap( 4385): Grow heap (frag case) to 18.064MB for 3688532-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(4386f540): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(43855150): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4385): Initializing JXcore engine
,W/jxcore-log( 4385): JXcore engine is ready
,W/jxcore-log( 4385): Starting JXcore engine
,W/jxcore-log( 4385): Platform android
W/jxcore-log( 4385): 
,W/jxcore-log( 4385): Process ARCH arm
W/jxcore-log( 4385): 
,D/PMS     (  905): releaseWL(43732758): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4385): JXcore Cordova bridge is ready!
I/jxcore-log( 4385): 
,W/jxcore-log( 4385): JXcore engine is started
,I/chromium( 4385): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4385): Toggling radios to true
I/jxcore-log( 4385): 
,D/BluetoothAdapter( 4385): enable(): BT is already enabled..!
,D/WifiManager( 4385): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1272
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
W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
D/WifiManager( 4385): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 4385): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): TDLS: Tear down peers
,I/wpa_supplicant( 1183): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4385): Radios toggled
I/jxcore-log( 4385): 
,I/jxcore-log( 4385): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4385): 
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4385, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1183): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1183): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1183): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7491bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1183): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1183): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0,x8b15 len=20
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  905):    returned true
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(43814e18): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  905):    returned true
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): Fast associate: Old scan results
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  905):    returned true
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=21039 mDataStallAlarmIntent=PendingIntent{425ee6c0: PendingIntentRecord{41c2a0f8 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
D/WISPrService( 3772): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3772): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiService(  905): New client listening to asynchronous messages
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
V/NativeCrypto( 1355): Read error: ssl=0x661ecfa8: I/O error during system call, Connection timed out
,D/WISPrService( 3772): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
V/NativeCrypto( 1355): SSL shutdown failed: ssl=0x661ecfa8: I/O error during system call, Broken pipe
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/PMS     (  905): acquireWL(42ee7b50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3772): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] entry_id:3   entry:0xb78b2590  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb78b22a8  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb78b6e40  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb78b6d90  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb78b6f70  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb78adc20  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb78b2458  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb78b21b8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/PMS     (  905): acquireWL(426e6590): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1355/10029)
,D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  905):    returned false
,I//system/bin/ip(  364): RTNETLINK answers: No such process
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
D/PMS     (  905): releaseWL(42ee7b50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  905): releaseWL(426e6590): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421a2d10
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421a2d10, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421ade10
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@421f19a0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,W/PMS     (  905): mWirelessDisplayManager is null
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 318ms
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@442dc800)
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
D/PMN     (  905): wakingUp
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4385
,I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
I/WindowManager(  905): No lock screen! windowToken=null
,D/NfcService( 1254): applyRouting -2
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): acquireWL(4260ad98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMN     (  905): onScreenOn
D/PMS     (  905): acquireWL(4269ef70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMS     (  905): releaseWL(4260ad98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/BatteryService(  905): n_update end
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(4269ef70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/MtpService( 2706): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2706): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): applyRouting -2
,D/AutoSetting( 1321): receiver - intent: android.intent.action.USER_PRESENT
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/PMS     (  905): acquireWL(4245f420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  905): releaseWL(4245f420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
,D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/TetherSettings( 3772): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3772): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3772): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3772): Cust_ConnectToPC   : spcsc>false
D/        ( 3772): Cust_ConnectToPC   : IPT>true
D/        ( 3772): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3772): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3772): hasRemovableStorageSlot: true
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doBoolean: SET pno 0
D/SmartNS_Utility( 3772): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3772): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:On
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  905):    returned true
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  905):    returned true
I/PSReceiver( 3772): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3772): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3772): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3772):  defaultType:0
V/SRS_Proc(  372): ParamSet string: screen_state=on
V/NotificationService(  905): batLight: Full, plugged
W/ContextImpl( 3772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/ClockThread( 1117): stop update clock
D/NetworkPolicy(  905): updateScreenOn: false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4447 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  905): NoActiveNetworkState
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
,I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42ad31e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(42ad31e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,I/NetworkMonitor( 3823): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3823/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4235/10100)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4235/10100)
D/PMS     (  905): acquireWL(442dfd58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(442dfd58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42728110): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1746): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): onScreenOn: 1453042962660
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1746): onScreenOn: 1453042962660
D/PMS     (  905): releaseWL(42728110): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4447): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(4426eff0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4447 1000 null
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421ade10
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421ade10, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@421f19a0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): releaseWL(4426eff0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  905): acquireWL(43de31f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=21040 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  905): doBoolean: SET pno 1
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/PMS     (  905): acquireWL(4267e6c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/SmartSyncUtils( 4447): getMobilePolicyEnabled, result = true
,D/Process (  905): killProcessQuiet, pid=3823
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1183): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
D/wpa_supplicant( 1183): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 3
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 1
I/wpa_supplicant( 1183): wpa_s->is_screen_on 1
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): selected network = 2
D/wpa_supplicant( 1183): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb74934e8  current_ssid=0x0
D/wpa_supplicant( 1183): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1183): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1183): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1183): check if in concurrent case
I/wpa_supplicant( 1183): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1183): RSN: PMKSA cache search - network_ctx=0xb74934e8 try_opportunistic=0
D/wpa_supplicant( 1183): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1183): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1183): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1183): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 6
D/wpa_supplican,t( 1183): nl80211: Unsubscribe mgmt frames handle 0xb7492718 (mode change)
D/wpa_supplicant( 1183): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7492718
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb7492718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1183):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183):   * freq=2412
D/wpa_supplicant( 1183):   * Auth Type 0
D/wpa_supplicant( 1183):   * WPA Versions 0x2
I/ActivityManager(  905): Killing 3823:com.google.android.music:main/u0a154 (adj 15): empty #17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1183): nl80211: Connect request send successfully
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:Off
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1183): get_ip_address source addr = 02000000
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET pno 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Recipient 3823
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 3823): Died!
D/PMS     (  905): releaseWL(4267e6c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (489) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-46
I/wpa_supplicant( 1183): tsf=0000000023390088
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-52
I/wpa_supplicant( 1183): tsf=0000000023390106
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1183): ssid=01ABC
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-52
I/wpa_supplicant( 1183): tsf=0000000106496111
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-79
I/wpa_supplicant( 1183): tsf=0000000023390118
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4466 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 23390088, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 23390106, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 106496111, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 23390118, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
V/SRS_Proc(  372): ParamSet string: screen_state=off
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/BatSI   (  905): WIFI scan stopped for: 440a0300 uid:1000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
D/NetworkPolicy(  905): updateScreenOn: false
I/MusicStore( 4466): Database version: 95
,W/ContextImpl( 4466): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/AutoSetting( 1321): service - mHandler: cancel location update
,D/AutoSetting( 1321): service -           changes count: 0
,W/ContextImpl( 4466): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] getTotalRam: 1873 Mb
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Connect event
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1183): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1183): Add randomness: count=8 entropy=1
I/wpa_supplicant( 1183): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): TDLS: Remove peers on association
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1183): EAPOL: enable timer tick
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1183): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): Get randomness: len=32 entropy=2
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSs,id ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb74929f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fbbb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    broadcast key
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
,I/wpa_supplicant( 1183): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1183): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1183): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/PMS     (  905): acquireWL(42fa2868): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1183): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=6
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1183): set send_ind_to_ndc = 0
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1183): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1183): EAPOL authentication completed successfully
I/wpa_supplicant( 1183): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4466): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/PMS     (  905): releaseWL(42fa2868): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(430fda08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/PMS     (  905): releaseWL(430fda08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1746): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): onScreenOff
D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1746): onScreenOff
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3772): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3772): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiNative-wlan0(  905): doBoolean: SET pno 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1183): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  905):    returned true
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 1
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/ContextImpl( 4466): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1183): nl80211: Event message available
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/wpa_supplicant( 1183): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiNative-wlan0(  905):    returned null
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4466): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(44370560): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4256b348 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4256b348 target=com.android.internal.util.StateMachine$SmHandler }
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4466, uid=10154, userID:0
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,I/MediaRouter( 4466): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
D/MediaRouterService(  905): Client com.google.android.music (pid 4466): Registered
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4466/10154)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2706/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4488 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4466): getSelectedRoute
,I/NetworkMonitor( 4466): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4466/10154)
,D/ACRA    ( 4488): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  905): killProcessQuiet, pid=3805
,D/ACRA    ( 4488): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4488): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4466, uid=10154, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(431008b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
I/ActivityManager(  905): Killing 3805:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/PMS     (  905): releaseWL(431008b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/SystemClassLoaderAdder( 4488): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4488): Preparing secondary program dexes.
V/DexLibLoader( 4488): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4488): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4488): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4488): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4488): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4488): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4488): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4488): Dex already copied
D/OdexVerifier( 4488): Odex verification is skipped.
V/DexLibLoader( 4488): Creating class loader
V/DexLibLoader( 4488): Finished creating class loader
V/DexLibLoader( 4488): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4488): Dex already copied
D/OdexVerifier( 4488): Odex verification is skipped.
,V/DexLibLoader( 4488): Creating class loader
V/DexLibLoader( 4488): Finished creating class loader
V/DexLibLoader( 4488): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4488): Dex already copied
D/OdexVerifier( 4488): Odex verification is skipped.
,V/DexLibLoader( 4488): Creating class loader
,V/DexLibLoader( 4488): Finished creating class loader
V/DexLibLoader( 4488): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4488): Dex already copied
D/OdexVerifier( 4488): Odex verification is skipped.
,V/DexLibLoader( 4488): Creating class loader
,V/DexLibLoader( 4488): Finished creating class loader
,V/DexLibLoader( 4488): Verifying classes from secondary dexes.
,D/DexLibLoader( 4488): DexLibLoader.ensureDexLoaded took 18 ms
,I/ActivityManager(  905): Recipient 3805
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{42b3fea8 u0 com.test.thalitest/.MainActivity t2}
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(44370560): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [3][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  905): WAN detection
,D/WISPrService( 3772): >>>>>WISPrService start isConnected = true<<<<<
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
,D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@424882a8
,D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
,D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
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
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(433d2470): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000),
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1,
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  364): RTNETLINK answers: No such process,
,I/logwrapper(  364): /system/bin/ip terminated by exit(2),
,W/dalvikvm( 4488): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4488): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4488): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
W/dalvikvm( 4488): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4488): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4488): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/dalvikvm( 4488): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/PMS     (  905): releaseWL(433d2470): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/wpa_supplicant( 1183): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1183): EAPOL: disable timer tick
,W/dalvikvm( 4488): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4488): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4488): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4488): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4488): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4488): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4172
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4172:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4172
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/AutoSetting( 1321): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4547 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1321): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1321): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1321): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
,W/fb4a(:<default>):UserScope( 4488): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4488): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4547): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4547): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4547): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4547): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4488): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/PMS     (  905): releaseWL(43814e18): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4561 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,I/ActivityManager(  905): Killing 4058:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=4058
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/jxcore-log( 4385): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4385): 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4547/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4547/10079)
,D/PMS     (  905): acquireWL(4433a070): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4547/10079)
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,I/NetworkMonitor( 4466): type=WIFI subType= reason=null isConnected=true
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1453042913529 min interval config: 0 actual interval: 51141
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4466/10154)
D/PMS     (  905): acquireWL(42a44fc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4235/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4547/10079)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): releaseWL(4433a070): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3862/10053)
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4235/10100)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1371): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): acquireWL(42f03d18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/CheckinService( 2184): Checking schedule, now: 1453042964699 next: 1453042943491
I/CheckinService( 2184): active receiver: enabled
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
D/PMS     (  905): acquireWL(426d0748): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Recipient 4058
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 9.961MB for 84664-byte allocation
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AccTypeManager( 1371): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1371): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 9.975MB for 28144-byte allocation
D/PMS     (  905): releaseWL(426d0748): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(42f03d18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4579 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4204
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/CheckinService( 2184): Preparing to send checkin request
,I/EventLogService( 2184): Accumulating logs since 1453042908598
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4488): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4488): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4488): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
I/ActivityManager(  905): Killing 4204:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4488): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4488): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4488): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4488): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4488): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4488): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4488): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4488): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4488): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4488): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4488): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/ExternalAccountType( 1371): Unsupported attribute readOnly
I/ActivityManager(  905): Recipient 4204
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 10.051MB for 39954-byte allocation
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4579): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/dalvikvm-heap( 4488): Grow heap (frag case) to 10.127MB for 79892-byte allocation
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4579/10151)
,I/dalvikvm-heap( 4488): Grow heap (frag case) to 10.285MB for 75760-byte allocation
,V/WebViewChromiumFactoryProvider( 4579): Binding Chromium to main looper Looper (main, tid 1) {41b01c98}
,I/LibraryLoader( 4579): Expected native library version number "",actual native library version number ""
,I/chromium( 4579): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4579): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(436d5170): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/PMS     (  905): acquireWL(43697598): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  905): releaseWL(436d5170): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424b3d88 u0 ReceiverList{42465a58 4488 com.facebook.katana/10027/u0 remote:41d82150}}
,E/AudioManagerAndroid( 4579): BLUETOOTH permission is missing!
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424b3d88 u0 ReceiverList{42465a58 4488 com.facebook.katana/10027/u0 remote:41d82150}}
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4610 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/Adreno-EGL( 4579): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4579): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4579): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4579): Local Branch: 
I/Adreno-EGL( 4579): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4579): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4579):                  aa63bbd948f41d15fc72f585e
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4249f988 u0 ReceiverList{42456f40 4488 com.facebook.katana/10027/u0 remote:41cc9e80}}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/NSApplication( 4579): Starting up...
,W/dalvikvm( 4610): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4610): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4610): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4610): install
,I/MultiDex( 4610): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4579/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4579/10151)
I/MultiDex( 4610): loading existing secondary dex files
I/MultiDex( 4610): load found 3 secondary dex files
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/MultiDex( 4610): install done
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3599/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3599/10160)
,D/Process (  905): killProcessQuiet, pid=4235
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Killing 4235:com.google.android.apps.docs/u0a100 (adj 15): empty #17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(421c0998): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(421c0998): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Recipient 4235
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4610): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4610): VFY: unable to resolve instance field 36
,W/dalvikvm( 4610): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4610): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4447): isEpsOn(), nState = 0
D/SmartSyncUtils( 4447): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4447): isEpsOn(), nState = 0
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@421f19a0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@421f19a0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@421f19a0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@421f19a0
D/WifiService(  905): New client listening to asynchronous messages
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2706/10021)
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42410ca0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42410ca0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
I/ProviderInstaller( 4610): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 4385): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4385): 
,I/jxcore-log( 4385): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4385): 
,W/dalvikvm( 4610): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4610): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4610): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4610): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4610): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4610): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4610): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/AutoSetting( 1321): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4547): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4547): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4579/10151)
D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1321): service - onStartCommand() screen is off, don't request location
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1321): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1321): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3599/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3599/10160)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/jxcore-log( 4385): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4385): 
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,I/jxcore-log( 4385): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4385): 
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
I/WVCdm   (  372): CdmEngine::OpenSession
I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
I/jxcore-log( 4385): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4385): 
I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/jxcore-log( 4385): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4385): 
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/NativeLibraryUtils( 4610): Install completed successfully. count=14 extracted=0
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,D/LocationInitializer( 2184): Restart initialization of location
,E/MDM     ( 1222): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1355): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1355): Proximity feature is not enabled.
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2836460438
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  905): acquireWL(435cdd90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  905): releaseWL(435cdd90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/jxcore-log( 4385): Test app app.js loaded
I/jxcore-log( 4385): 
,I/Choreographer( 4385): Skipped 274 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4385): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4385): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b150d8 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  905): releaseWL(43de31f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4385): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/Settings( 4610): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4610): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4610): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4610): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4610): Local Branch: 
I/Adreno-EGL( 4610): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4610): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4610):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=3580879129
,I/WVCdm   (  372): CdmEngine::CloseSession
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4610/10029)
,I/Adreno-EGL( 4610): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4610): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4610): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4610): Local Branch: 
I/Adreno-EGL( 4610): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4610): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4610):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4610): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4610): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4610): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4610): Local Branch: 
I/Adreno-EGL( 4610): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4610): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4610):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
,D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =18c5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e3c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 242
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2184): Sending checkin request (12081 bytes)
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=9 [22][2][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,I/CheckinTask( 2184): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2184): Checking schedule, now: 1453042967329 next: 1453565904321
,I/CheckinService( 2184): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
,D/CheckinService( 2184): Recording last checkin time for package unspecified as 1453042967345
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
D/PMS     (  905): releaseWL(42a44fc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/PMS     (  905): acquireWL(4374e828): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
D/libc    ( 1355): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1355): [NET] getaddrinfo-,err=8
D/libc    ( 1355): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1355): [NET] getaddrinfo-, 1
D/libc    ( 1355): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =263b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
W/fb4a(:<default>):UserScope( 4488): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4488): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 142
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1355): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/libc    ( 1355): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1355): [NET] getaddrinfo-,err=8
,D/libc    ( 1355): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1355): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4488): Called registerBroadcastReceiver twice.
,D/PMS     (  905): acquireWL(43ee9060): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/PMS     (  905): releaseWL(4374e828): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1355/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/PMS     (  905): releaseWL(43ee9060): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(442ad9a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1355/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1355/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  905): releaseWL(442ad9a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4488/10027)
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  905): acquireWL(42596dc8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4466 10154 null
,W/ContextImpl( 4466): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4466, uid=10154, userID:0
,I/MusicLeanback( 4466): Conditions not met for autocaching.
,I/MusicLeanback( 4466): Stop autocaching.
D/PMS     (  905): releaseWL(42596dc8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4466): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  905): releaseWL(43697598): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=11 [9][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1512): service - handleMessage() stop self
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4253
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4253:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4253
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4579): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=4222
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4222:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4222
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3862
,I/ActivityManager(  905): Killing 3862:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3862
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1371): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4676 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
W/AccTypeManager( 1371): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1371): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsUpdated
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1371): Unsupported attribute readOnly,
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4676): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4676): MmsConfig.loadMmsSettings
,W/dalvikvm( 4676): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4676): VFY: unable to resolve instance field 36
,W/dalvikvm( 4676): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4676): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4699 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4676, uid=10111, userID:0
,W/Settings( 4676): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4699): onCreate
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4676, uid=10111, userID:0
,V/GetPrviateResource( 4699): GetPrviateResource
,V/GetPrviateResource( 4699): GetPrviateResource
,D/MmsCustomizationProvider( 4699): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4676, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4676, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4676, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4676, uid=10111, userID:0
D/PMS     (  905): acquireWL(43f102d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4676 10111 null
,W/PackageManager(  905): Unable to load service info ResolveInfo{43712808 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/MmsCustomizationProvider( 4699): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1321): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1321): handle notify Blinkfeed plugin client changed
I/IcingCorporaProvider( 2806): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Babel   ( 4676): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4676): MmsConfig.loadFromDatabase
,E/Babel   ( 4676): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4676): MmsConfig.loadFromResources
E/Babel   ( 4676): canonicalizeMccMnc: invalid mccmnc nullnull
,I/ProviderInstaller( 4676): Installed default security provider GmsCore_OpenSSL
,I/Babel   ( 4676): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4699): sense_version=6.0
,D/BTAccessoryUtil( 4699): createReceiver
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/BTAccessoryUtil( 4699): registerReceiver return intent = null
D/MessageCustFlag( 4699): sku_id=99
,W/SystemReader( 4699): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4699): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4699): networkCode: 
,D/MessageCustFlag( 4699): sku_id=99
D/MmsConfig( 4699): SIE smsPri: null
,D/MmsConfig( 4699): networkCode: 
,D/HtcTelephonyCapability( 4699): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4699): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4699): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4699): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  905): acquireWL(43f0e760): PARTIAL_WAKE_LOCK  AsyncService 0x1 3599 10160 null
,D/PMS     (  905): acquireWL(4431dcc8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43f102d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  905): releaseWL(4431dcc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): releaseWL(43f0e760): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  905): acquireWL(43eab670): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/ActivityManager(  905): Killing 4275:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=4275
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Recipient 4275
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2184): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  905): Resuming delayed broadcast
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Icing   ( 2184): updateResources: need to parse f{com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(424de7e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(424de7e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(41f45330): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(41f45330): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(41c7bdc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(41c7bdc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42c8db88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42c8db88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2806): UpdateCorporaTask done [took 614 ms] updated apps [took 614 ms] 
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b94bf8 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,D/PMS     (  905): acquireWL(4324edc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{43f2b6e0: PendingIntentRecord{4273af28 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=120223, Int=0
,D/PMS     (  905): releaseWL(4324edc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(435a7c00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=11 [9][1][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(42332328): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(435a7c00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42332328): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42350f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  905): releaseWL(42350f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42088fa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(4259ce18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
,D/PMS     (  905): acquireWL(4263f3e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,I/GamesSyncServiceMain( 2184): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 2184): Failed to execute periodic sync, missing client context - aborting
D/PMS     (  905): releaseWL(4259ce18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42088fa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4243a1c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  905): releaseWL(4243a1c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4217e360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(4263f3e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4217e360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42abd6d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
D/PMS     (  905): releaseWL(42abd6d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(425766c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(43eab670): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43faebf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1453042976827 tag=VacuumService
,D/PMS     (  905): acquireWL(425c57d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43faebf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425766c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42ad2928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425c57d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42ad2928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42ed9ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b94bf8 -
D/PMS     (  905): releaseWL(42ed9ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(441c0618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
D/PMS     (  905): releaseWL(441c0618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(42708e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42708e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42abe070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42720168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42abe070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/Messaging( 4699): mNeedToUpdateDate2 start
,D/MmsConfig( 4699): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4699): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4699): 
D/MmsAsyncWorkHandler( 4699): HM tk = 20001
D/ReportIndicatorCache( 4699): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4699): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b0f1b0
,I/Messaging( 4699): mccmnc> 
D/DraftCache( 4699): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4699): [DraftCache/1] refresh
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsConfig( 4699): networkCode: 
D/MmsSmsV2Provider( 1241):  phoneType = -1
D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4699): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 4699): sense_version=6.0
D/PhoneStorageUtil( 4699): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4699): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4699): createReceiver
,D/Jerry   ( 4699): start to preload cursor >>>>>>>
D/Messaging( 4699): mNeedToUpdateDate2: false
D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1241): Update uri=content://mms, match=0
,V/MmsProvider( 1241): selection=st=129 AND m_type!=134
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Messaging( 4699): Reset downloading state: 0
V/MmsSystemEventReceiver( 4699): TransactionService is going to be woken up.
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,V/TransactionService( 4699): 1-Creating TransactionService
V/TransactionService( 4699): onStartCommand: 1
,D/MmsSystemEventReceiver( 4699): unRegisterForConnectionStateChanges
V/TransactionService( 4699): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4699): Loading previous transactions.
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): device_type: 1
D/Messaging( 4699): ViewCache CreatePreload
,D/Messaging( 4699): ViewCache CreatePreloadOnlyMultipleOpsList
D/TransactionService( 4699): Force set service start id to 1
V/TransactionService( 4699): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4699): unRegisterForConnectionStateChanges
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1241): sku_id=99
,D/TransactionService( 4699): stopSelfResult: true, mLastHandledServiceId: 1
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 8839 seconds from now (1453042977385)
,V/TransactionService( 4699): Destroying TransactionService
,D/Cust_MMSMS( 4699): _has_set_default_values_2=true
,V/TransactionService( 4699): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/DraftCache( 4699): [DraftCache/466] rebuildCache
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/MsgPreferenceUtils( 4699): def_index: 0
,D/MsgPreferenceUtils( 4699): globalIndex = 1
,D/Messaging( 4699): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/MsgPreferenceUtils( 4699): phone state: true
D/MsgPreferenceUtils( 4699): sd state: false
,D/MsgPreferenceUtils( 4699): vIndex = 0
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/Jerry   ( 1241): URI_DRAFT
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/DraftCache( 4699): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4699): [DraftCache/466] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4699): 
D/MmsAsyncWorkHandler( 4699): HM tk = 20002
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): sku_id=99
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): sku_id=99
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cd47 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 256
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [8][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(42720168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4346ec00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  905): releaseWL(4346ec00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42ff7d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024927
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025245
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025253
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026680
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026695
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  905): releaseWL(42ff7d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4434f058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4218ebe8: PendingIntentRecord{41c27f28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=123777, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4434f058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4676): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  905): acquireWL(42ce74a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PMS     (  905): releaseWL(42ce74a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43d17d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{4306ff18: PendingIntentRecord{42666268 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136681, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1355/10029)
,D/PMS     (  905): releaseWL(43d17d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1321): service - mHandler: update timezone
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1512): service - onCreate()
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/DotMatrix( 1563): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1512): service - mHandler: update timezone
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1512): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1512): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e24168 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 2 11
,D/AutoSetting( 1321): service - has update message, not stop
,D/AutoSetting( 1321): service - mHandler: update timezone
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1563): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1512): service - mHandler: update timezone
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1512): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1512): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e3b3b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 8 2 11
,D/PMS     (  905): acquireWL(43826718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{423c9ce8: PendingIntentRecord{4216bef8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142500, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(44332178): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(43826718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8e4b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): acquireWL(437d75d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(437d75d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): releaseWL(44332178): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4436eee0 u0 com.htc.htclocationservice/.AutoSettingService}
,I/ClearcutLoggerApiImpl( 1355): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1321): service - handleMessage() stop self
,D/AutoSetting( 1321): service - handleMessage() quit looper
,D/AutoSetting( 1321): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=4307
,I/ActivityManager(  905): Killing 4307:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4307
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1512): service - handleMessage() stop self
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4322
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4322:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4322
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4262a0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{421ac500: PendingIntentRecord{435187f8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172688, Int=0
,D/PMS     (  905): releaseWL(4262a0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(43bb5d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4218ebe8: PendingIntentRecord{41c27f28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=183776, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43bb5d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44337558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44337558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(442a4558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(442a4558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(426d10c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{4218ebe8: PendingIntentRecord{41c27f28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=243777, Int=0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
D/PMS     (  905): releaseWL(426d10c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(435cc130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(435cc130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/PMS     (  905): acquireWL(43de70f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43de70f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(435c3c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4218ebe8: PendingIntentRecord{41c27f28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=303777, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(435c3c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4426c9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4426c9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4385): --= Surplus to requirements =--
I/jxcore-log( 4385): 
I/jxcore-log( 4385): ****TEST TOOK:  ms ****
I/jxcore-log( 4385): 
,I/jxcore-log( 4385): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4385): 
,E/cutils-trace( 4795): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4795): ====startRecUseTime====
D/htc.customization.log.level( 4795):  is 
,W/CustomizationLogLevel( 4795): Level value is invalid, use default level 2
,D/CustomizationManager( 4795):  Read ACC file spent 0.100 (s)
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
,V/CustomizationCIDLoader( 4795): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4795): Parsing tag category name = system
,I/CustomizationCIDLoader( 4795): Parsing tag category name = application
I/CustomizationCIDLoader( 4795): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 4795): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4795): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4795): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4795): Parsing tag category name = Settings
D/CustomizationManager( 4795):  Read CID file spent 0.153 (s)
,D/CustomizationManager( 4795):  All configurations done spent 0.154 (s)
,W/HtcNativeFlag( 4795): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4795): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4795): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4795): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4795, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4385
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905): Killing 4385:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  905):   Force finishing activity ActivityRecord{42b3fea8 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  905): Copying FileAsset 0x68586290 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  905): channel '41c23790 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '41c23790 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '41c23790 com.test.thalitest.MainActivity (s)'
I/WindowManager(  905): WINDOW DIED Window{41c23790 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
,W/WindowManager(  905): Failed looking up window
W/WindowManager(  905): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@43ef3cc0 does not exist
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  905): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  905): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  905): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  905): WIN DEATH: null
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4385 uid 10389
,W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
,W/PackageSettings(  905): Skipping PackageSetting{422c8a20 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
,D/AccTypeManager( 1371): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): acquireWL(4429a5b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PMS     (  905): releaseWL(4429a5b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1287): Cleaning up data for package: com.test.thalitest
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/[PluginManager]RegisterService( 1321): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/[PluginManager]RegisterService( 1321): handle notify Blinkfeed plugin client changed
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/AccTypeManager( 1371): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1371): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/IcingCorporaProvider( 2806): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
,E/ExternalAccountType( 1371): Unsupported attribute readOnly
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4811 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  905): acquireWL(4426c9c0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2806): UpdateCorporaTask done [took 414 ms] updated apps [took 414 ms] 
,E/SQLiteDatabase( 4811): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4811): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4811): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4811): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4811): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4811): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4811): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4811): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4811): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4811): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4811): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4811): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4811): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4811): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4811): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4811): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4811): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4811): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4811): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4811): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4811): ,	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4811): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4811): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4811): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4811): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4811): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4811): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4811): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4811): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4811): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4811): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4811): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4811): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4811): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4811): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4811): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4811): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4811): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4811): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4811): threadid=11: thread exiting with uncaught exception (group=0x416cfe30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4811): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4811): Process: com.google.android.apps.docs, PID: 4811
E/AndroidRuntime( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4811): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4811): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4811): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4811): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4811): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4811): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  905): Can't write: system_app_crash
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
,D/Process ( 4811): killProcess, pid=4811
,D/Process ( 4811): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4830 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4811
,I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4811) has died.
,W/ContextImpl( 4830): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4842 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4830): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4830): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4830): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4830): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4830): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4830): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4830): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4830): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4830): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4830): threadid=10: thread exiting with uncaught exception (group=0x416cfe30)
E/AndroidRuntime( 4830): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4830): Process: com.android.keychain, PID: 4830
E/AndroidRuntime( 4830): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4830): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4830): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4830): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4830): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4830): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4830): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4830): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/AppTag  ( 4842): getInstance(Context context)
,D/AppTag  ( 4842): getInstance(Context context)
,D/Process ( 4830): killProcess, pid=4830
,D/Process ( 4830): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/AppTag  ( 4842): onCreate()
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453043192333.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  905): Recipient 4830
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.android.keychain (pid 4830) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/PMS     (  905): acquireWL(42ce7438): PARTIAL_WAKE_LOCK  AsyncService 0x1 3599 10160 null
,D/PMS     (  905): releaseWL(42ce7438): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 3991): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/Process (  905): killProcessQuiet, pid=4030
,I/ActivityManager(  905): Killing 4030:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2184): Clearing selected account for com.test.thalitest
,I/ActivityManager(  905): Recipient 4030
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/LocationSettingsChecker( 2184): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e8b2008
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5caaf2a0
,W/dalvikvm( 2184): threadid=44: thread exiting with uncaught exception (group=0x416cfe30)
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
E/AndroidRuntime( 2184): FATAL EXCEPTION: PlayGamesAsyncThread1
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
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2184): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
D/Process ( 2184): killProcess, pid=2184
D/Process ( 2184): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b94bf8 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/ActivityManager(  905): Recipient 2184
D/PMS     (  905): handleWLDeath(4426c9c0): PARTIAL_WAKE_LOCK  Icing 0x1
,D/WifiService(  905): Client connection lost with reason: 4
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.google.android.gms (pid 2184) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10998ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10997ms
,I/ActivityManager(  905): Resuming delayed broadcast
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10989ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10988ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20988ms
,E/SQLiteLog( 1355): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1355): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x64018590
,W/dalvikvm( 1355): threadid=1: thread exiting with uncaught exception (group=0x416cfe30)
,E/AndroidRuntime( 1355): FATAL EXCEPTION: main
E/AndroidRuntime( 1355): Process: com.google.process.gapps, PID: 1355
E/AndroidRuntime( 1355): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1355): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1355): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1355): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1355): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1355): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1355): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1355): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1355): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1355): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1355): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1355): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1355): 	... 10 more
,E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
,E/DropBoxManagerService(  905): Can't write: system_app_crash
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
,I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4876 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1355): killProcess, pid=1355
D/Process ( 1355): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/DeviceManagement( 4876): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4876 dbg=false s=true
,I/DeviceManagement( 4876): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4876): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/ActivityManager(  905): Recipient 1355
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.process.gapps (pid 1355) has died.
D/WifiService(  905): Client connection lost with reason: 4
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30803ms
,I/DeviceManagement( 4876): WorkflowService: Starting workflow service
,I/DeviceManagement( 4876): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b2de30] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4876): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4876): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4876): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4876): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4890 uid=10099 gids={50099, 3003, 5012}
,W/PackageManager(  905): Unable to load service info ResolveInfo{4307d4f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/DeviceManagement( 4876): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4876): SessionStateController: Checking invariants...

```
