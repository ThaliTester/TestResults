#### Test 506502783fcf234_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  912):    returned true
E/cutils-trace( 4404): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4404): ====startRecUseTime====
D/htc.customization.log.level( 4404):  is 
W/CustomizationLogLevel( 4404): Level value is invalid, use default level 2
D/CustomizationManager( 4404):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4404): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4404): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4404): Parsing tag category name = system
I/CustomizationCIDLoader( 4404): Parsing tag category name = application
I/CustomizationCIDLoader( 4404): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4404): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4404): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4404): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4404): Parsing tag category name = Settings
D/CustomizationManager( 4404):  Read CID file spent 0.095 (s)
D/CustomizationManager( 4404):  All configurations done spent 0.096 (s)
W/HtcNativeFlag( 4404): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4404): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4404): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4404): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  912): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  912): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  912): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4404
D/PMS     (  912): acquireHCC(43e22c90): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 912 1000 null
D/PMS     (  912): acquireHCC(44004bc8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 912 1000 null
W/asset   (  912): Copying FileAsset 0x6303f438 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  912): @test_code: getHtcIntentFlag: 0 obj: 1136192496
D/PMS     (  912): acquireWL(43117e28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 912 1000 null
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41e37c28
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  912): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4415 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4415): Copying FileAsset 0x5c8b2428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4415): Binding Chromium to main looper Looper (main, tid 1) {41cd03c8}
I/LibraryLoader( 4415): Expected native library version number "",actual native library version number ""
I/chromium( 4415): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4415): Initializing chromium process, renderers=0
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42575670:true
D/PMS     (  912): acquireWL(43ec4798): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  912): acquireWL(44082e88): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  912): releaseWL(43ec4798): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4415): 1104043520: getState(). Returning 12
I/Adreno-EGL( 4415): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4415): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4415): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4415): Local Branch: 
I/Adreno-EGL( 4415): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4415): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4415):                  aa63bbd948f41d15fc72f585e
W/chromium( 4415): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4415): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4415): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4415): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4415): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4415): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4415): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4415): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4415): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4415): CordovaWebView is running on device made by: HTC
,W/AwContents( 4415): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  912): Disable input method client, pid=1270
,I/ActivityManager(  912): Displayed com.test.thalitest/.MainActivity: +266ms
W/ResourceType( 4415): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4415): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41d174b0, mServedView=org.apache.cordova.engine.SystemWebView{41cdd118 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4415): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  912): Enable input method client, pid=4415
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/PMS     (  912): releaseWL(43117e28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4415): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4415): JniHelper::setJavaVM(0x4188f010), pthread_self() = 1663646488
,D/JX-Cordova( 4415): jxcore cordova android initializing
,I/dalvikvm-heap( 4415): Grow heap (frag case) to 11.631MB for 144892-byte allocation
,I/dalvikvm-heap( 4415): Grow heap (frag case) to 11.747MB for 217334-byte allocation
,I/dalvikvm-heap( 4415): Grow heap (frag case) to 11.922MB for 325996-byte allocation
,I/dalvikvm-heap( 4415): Grow heap (frag case) to 12.197MB for 488990-byte allocation
,I/dalvikvm-heap( 4415): Grow heap (frag case) to 12.603MB for 733480-byte allocation
,I/dalvikvm-heap( 4415): Grow heap (frag case) to 14.050MB for 1650320-byte allocation
,I/dalvikvm-heap( 4415): Grow heap (frag case) to 15.465MB for 2475476-byte allocation
,I/dalvikvm-heap( 4415): Grow heap (frag case) to 17.392MB for 3713210-byte allocation
,D/WifiDataStallTracker(  912): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  912): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
W/jxcore-log( 4415): Initializing JXcore engine
,W/jxcore-log( 4415): JXcore engine is ready
D/WifiDataStallTracker(  912): updateDataStallInfo: mDataStallTxRxSum={txSum=123 rxSum=112} preTxRxSum={txSum=123 rxSum=112}
D/WifiDataStallTracker(  912): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  912): onDataStallAlarm: tag=19665 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=19666 delay=15s
D/PMS     (  912): acquireWL(44375e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
V/AlarmManager(  912): sending alarm PendingIntent{4253cb28: PendingIntentRecord{427188b8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=100494, Int=0
D/PMS     (  912): releaseWL(44375e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/CpuWake (  912): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  912): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  912): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>release mCpuPerf_Freq wakelock
W/CpuWake (  912): <<release mCpuPerf_Freq wakelock
D/PMS     (  912): releaseHCC(43e22c90): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  912): releaseHCC(44004bc8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4415): Starting JXcore engine
,W/jxcore-log( 4415): Platform android
W/jxcore-log( 4415): 
,W/jxcore-log( 4415): Process ARCH arm
W/jxcore-log( 4415): 
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,I/jxcore-log( 4415): JXcore Cordova bridge is ready!
I/jxcore-log( 4415): 
,W/jxcore-log( 4415): JXcore engine is started
,I/chromium( 4415): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  912): releaseWL(44082e88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4415): Toggling radios to true
I/jxcore-log( 4415): 
,D/BluetoothAdapter( 4415): enable(): BT is already enabled..!
,D/WifiManager( 4415): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  912): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  912): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  912): Settings:Agentvalue: 2
W/Settings:Agent(  912): >> traceCallingStack()
W/Settings:Agent(  912): Process.myPid(): 912
W/Settings:Agent(  912): Process.myTid(): 1268
W/Settings:Agent(  912): Process.myUid(): 1000
W/Settings:Agent(  912): 
W/Settings:Agent(  912): 
,W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  912): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  912): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  912): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  912): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  912): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  912): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  912): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  912): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  912): 
,W/Settings:Agent(  912): << traceCallingStack(): 0(ms)
D/WifiManager( 4415): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  912): doBoolean: DISCONNECT
,D/WifiManager( 4415): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): TDLS: Tear down peers
,I/wpa_supplicant( 1182): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4415): Radios toggled
I/jxcore-log( 4415): 
,D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  912): New client listening to asynchronous messages
D/WifiService(  912): setWifiEnabled: true pid=4415, uid=10389
E/WifiService(  912): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  912): isSprintWifiRestricted(): false
I/WifiService(  912): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  912): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4415): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4415): 
I/jxcore-log( 4415): Perf Test app loaded loaded
I/jxcore-log( 4415): 
I/Choreographer( 4415): Skipped 77 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4415): check test folder
I/jxcore-log( 4415): 
,I/jxcore-log( 4415): found test : ./testFindPeers.js
I/jxcore-log( 4415): 
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1182): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1182): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1182): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  912): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  912): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  912): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  912): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1182): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7971bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1182):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1182): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1182): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1182): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  912):    returned true
D/WifiPerfLock(  912): release()
D/WifiStateMachine(  912): PerfLock released for exiting ConnectedState
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED,
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 0,
I/wpa_supplicant( 1182): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
,D/ConnectivityService(  912): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  912): acquireWL(42864030): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 912 1000 null
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  912):    returned true
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
,D/Tethering(  912): interfaceStatusChanged wlan0, false
D/DhcpStateMachine(  912): [RunningState] Stop DHCP
D/Tethering(  912): [isWifi] getHotspotEnabled: false
,I/jxcore-log( 4415): found test : ./testSendData.js
I/jxcore-log( 4415): 
D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  912): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  912): doBoolean: RECONNECT
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): Fast associate: Old scan results
I/wpa_supplicant( 1182): wpa_supplicant_scan enter
I/wpa_supplicant( 1182): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1182): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1182): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1182): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-wlan0(  912):    returned true
D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=19666 mDataStallAlarmIntent=PendingIntent{430c30a8: PendingIntentRecord{427188b8 android broadcastIntent}}
D/WifiStateMachine(  912): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 0
I/wpa_supplicant( 1182): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  912):    returned true
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  912): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  912): Provision feature enable=false
,D/ConnectivityService(  912): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateMachine(  912): Exit handleNetworkDisconnect
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 3777): >>>>>WISPrService start isConnected = false<<<<<
D/UsbnetStateTracker(  912): isAvailable+-
D/UsbnetStateTracker(  912): reconnect
,D/UsbnetStateTracker(  912): isAvailable+-
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  912): default: reconnect()
D/MDST    (  912): default: setTeardownRequested(false)
D/MDST    (  912): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  912): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3777): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 3777): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3777): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  912): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  912): New client listening to asynchronous messages
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  912): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): handleConnectivityChange: resetting
,D/ConnectivityService(  912): resetConnections(wlan0, 3)
,V/NativeCrypto( 1353): Read error: ssl=0x66039f60: I/O error during system call, Connection timed out
D/libc    (  363): [NET] entry_id:3   entry:0xb8fbc590  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8fc0e40  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8fc0d90  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8fc0f70  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8fb7c20  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8fbc458  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb8fbc2a8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/PMS     (  912): acquireWL(43b9a418): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  912): acquireWL(42bbd118): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
,V/NativeCrypto( 1353): SSL shutdown failed: ssl=0x66039f60: I/O error during system call, Broken pipe
,D/WifiStateMachine(  912): startScan Pid: 912 Uid 1000
,D/WifiNative-wlan0(  912): doBoolean: SCAN
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  912):    returned false
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/ConnectivityService(  912): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/BatSI   (  912): WIFI scan started for: 650a0300 uid:1000
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
D/ConnectivityService(  912): reportInetCondition for net -1, percentage: 0 by  (1353/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
D/PMS     (  912): releaseWL(43b9a418): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  912): releaseWL(42bbd118): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  912): mActiveDefaultNetwork: -1
D/ConnectivityService(  912): handleInetConditionChange: no active default network - ignore
,I/chromium( 4415): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/PMS     (  912): Going to sleep due to screen timeout...
,I/ActivityManager(  912): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@423656e8
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = CM36282 Light sensor
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@423656e8, eanble = 0, strlen(mName) = 59
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  912): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d65da0
W/SensorService(  912): Listener[1] = com.htc.smartdim.sensor_eye@42834cb8
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  912): Couldn't get kernel wake lock stats
V/LightsService(  912): setLight #2: color=#0
D/qdlights(  912): set_light_buttons_func: on=0 brightness=0
V/LightsService(  912): setLight #0: color=#0
,D/WirelessDisplayService(  912): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  912): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  912): mWirelessDisplayManager is null
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  912): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING,
D/Tethering(  912): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  912): bSetPropertyMultiRAB:false
D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  912): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0,
I/Tethering(  912): ipv4Default null
,I/Tethering(  912): No IPv4 upstream interface, giving up.
,D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  912): acquireWL(44298fa8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(44298fa8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
,I/NetworkMonitor( 3835): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10076)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (3835/10154)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  912): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  912): NoActiveNetworkState
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (2718/10021)
,I/ActivityManager(  912): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4469 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/SurfaceControl(  912): Excessive delay in blankDisplay() while turning screen off: 320ms
D/PMS     (  912): nativeSetInteractive:false
,D/PMS     (  912): nativeSetInteractive:false done
D/PMS     (  912): nativeSetAutoSuspend:true
D/PMS     (  912): nativeSetAutoSuspend:true done
,D/HABCtrl (  912): TPE algorithm. remove timeout.
,D/PMS     (  912): OOBE c monitor 11
I/InputManager(  912): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  912): screenObserver, isScreenOn=false
D/NfcService( 1254): ScreenObserver: OFF
D/NfcService( 1254): applyRouting - 0
V/KeyguardServiceDelegate(  912): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43ece768)
D/NfcService( 1254): applyRouting -2
W/ResourceType( 4415): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4415): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41cdd118 VFEDH.C. .F...... 0,0-720,1134 #64}
I/InputMethodManagerService(  912): Disable input method client, pid=4415
D/PMN     (  912): wakingUp
D/PMS     (  912): acquireWL(43ee4940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,D/PMS     (  912): releaseWL(43ee4940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  912): **** SHOWN CALLED ****
D/PMS     (  912): acquireWL(44285de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
D/PMS     (  912): releaseWL(44285de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  912): No lock screen! windowToken=null
D/PMN     (  912): onScreenOn
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/MtpService( 2718): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1254): applyRouting - 0
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2718): [MTP][onReceive]-
D/WirelessDisplayService(  912): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/NfcService( 1254): applyRouting -2
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): acquireWL(43e1d438): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/ACRA    ( 4469): ACRA is enabled for com.facebook.katana, intializing...
D/PMS     (  912): releaseWL(43e1d438): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  912): ACTION_SCREEN_ON
I/AlarmManager(  912): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done recovering
I/AlarmManager(  912): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,D/ACRA    ( 4469): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4469): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/ClockThread( 1113): stop update clock
D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  912): doBoolean: SET pno 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:On
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  912):    returned true
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 1182): wpa_supplicant_scan enter
,D/WifiNative-wlan0(  912):    returned true
,V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
,D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  374): ParamSet string: screen_state=on
,D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  912): updateScreenOn: false
,W/SystemClassLoaderAdder( 4469): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4469): Preparing secondary program dexes.
V/DexLibLoader( 4469): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4469): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4469): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4469): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4469): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4469): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4469): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4469): Dex already copied
D/OdexVerifier( 4469): Odex verification is skipped.
,V/DexLibLoader( 4469): Creating class loader
,V/DexLibLoader( 4469): Finished creating class loader
V/DexLibLoader( 4469): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4469): Dex already copied
D/OdexVerifier( 4469): Odex verification is skipped.
,V/DexLibLoader( 4469): Creating class loader
,V/DexLibLoader( 4469): Finished creating class loader
V/DexLibLoader( 4469): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4469): Dex already copied
D/OdexVerifier( 4469): Odex verification is skipped.
,V/DexLibLoader( 4469): Creating class loader
,V/DexLibLoader( 4469): Finished creating class loader
,V/DexLibLoader( 4469): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4469): Dex already copied
D/OdexVerifier( 4469): Odex verification is skipped.
,V/DexLibLoader( 4469): Creating class loader
,V/DexLibLoader( 4469): Finished creating class loader
,V/DexLibLoader( 4469): Verifying classes from secondary dexes.
,D/DexLibLoader( 4469): DexLibLoader.ensureDexLoaded took 21 ms
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  912): acquireWL(43e20aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(43e20aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(43ec96a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1734): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1734): onScreenOn: 1450238254659
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1734): onScreenOn: 1450238254659
D/PMS     (  912): releaseWL(43ec96a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d65da0
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d65da0, eanble = 0, strlen(mName) = 91
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  912): Listener[0] = com.htc.smartdim.sensor_eye@42834cb8
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  912): goingToSleep
D/PMS     (  912): acquireWL(4365d6b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 912 1000 null
,D/PMS     (  912): releaseWL(4365d6b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  912): ACTION_SCREEN_OFF
I/AlarmManager(  912): [AlarmQueuing] screen off now: 
I/AlarmManager(  912): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=19667 mDataStallAlarmIntent=null
I/AlarmManager(  912): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  912): doBoolean: SET pno 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 0
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='1'
D/PMS     (  912): acquireWL(43469528): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 912 1000 null
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1182): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1182): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1182): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1182): nl80211: Survey data missing
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1182): Sorted scan results
I/wpa_supplicant( 1182): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
D/wpa_supplicant( 1182): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1182): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1182): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1182): wpa_supplicant_pick_network+
I/wpa_supplicant( 1182): Selecting BSS from priority group 1
I/wpa_supplicant( 1182): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1182): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1182): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1182):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1182):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1182): Start print parameters
I/wpa_supplicant( 1182): wpa_s->wpa_state is 3
I/wpa_supplicant( 1182): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1182): isConcurrentMode() is 0
I/wpa_supplicant( 1182): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1182): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1182): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1182): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1182): wpa_s->reassociate is 1
I/wpa_supplicant( 1182): wpa_s->is_screen_on 1
I/wpa_supplicant( 1182): wpa_s->ifname wlan0
I/wpa_supplicant( 1182): End print parameters
I/wpa_supplicant( 1182): selected network = 1
D/wpa_supplicant( 1182): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb79734e8  current_ssid=0x0
D/wpa_supplicant( 1182): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1182): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1182): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1182): check if in concurrent case
I/wpa_supplicant( 1182): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  912):    returned true
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 1182): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1182): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1182): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1182): RSN: PMKSA cache search - network_ctx=0xb79734e8 try_opportunistic=0
,D/wpa_supplicant( 1182): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1182): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1182): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1182): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1182): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 6
,D/wpa_supplicant( 1182): nl80211: Unsubscribe mgmt frames handle 0xb7972718 (mode change)
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1182): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7972718
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7972718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Connect (ifindex=22)
,D/wpa_supplicant( 1182):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1182):   * freq=2412
D/wpa_supplicant( 1182):   * Auth Type 0
D/wpa_supplicant( 1182):   * WPA Versions 0x2
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1182): nl80211: Connect request send successfully
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:Off
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1182): get_ip_address source addr = 02000000
I/wpa_supplicant( 1182): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  912):    returned true
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SET pno 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1182): reply (376) for get BSS: id=0
I/wpa_supplicant( 1182): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1182): freq=5220
I/wpa_supplicant( 1182): level=-49
I/wpa_supplicant( 1182): tsf=0000000021660464
I/wpa_supplicant( 1182): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1182): ssid=NG7005g
,I/wpa_supplicant( 1182): ====
I/wpa_supplicant( 1182): id=1
I/wpa_supplicant( 1182): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): freq=2412
I/wpa_supplicant( 1182): level=-50
I/wpa_supplicant( 1182): tsf=0000000104188065
I/wpa_supplicant( 1182): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1182): ssid=NG700
I/wpa_supplicant( 1182): ====
I/wpa_supplicant( 1182): id=2
I/wpa_supplicant( 1182): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1182): freq=2412
I/wpa_supplicant( 1182): level=-81
I/wpa_supplicant( 1182): tsf=0000000021660480
I/wpa_supplicant( 1182): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1182): ssid=Gonzos
I/wpa_supplicant( 1182): ####
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
D/PMS     (  912): releaseWL(43469528): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,V/SRS_Proc(  374): ParamSet string: screen_state=off
,D/WifiManager( 1220): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 21660464, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 104188065, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 21660480, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 3 to mScanResults
D/BatSI   (  912): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/NetworkPolicy(  912): updateScreenOn: false
,D/ContactMessageStore( 1238): start background delete task...
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/AutoSetting( 1337): service - mHandler: cancel location update
,D/AutoSetting( 1337): service -           changes count: 0
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  912): acquireWL(43762d48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(43762d48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43a977a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1734): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1734): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1734): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1734): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1734): onScreenOff
,D/PMS     (  912): releaseWL(43a977a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1182): nl80211: Connect event
D/wpa_supplicant( 1182): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1182): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1182): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1182): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1182): Add randomness: count=7 entropy=1
I/wpa_supplicant( 1182): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1182): TDLS: Remove peers on association
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1182): EAPOL: enable timer tick
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1182): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1182): Get randomness: len=32 entropy=2
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  912): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  912): WifiMonitor:get,MacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  912): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  912): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  912): Enter handleAssociatedWithEvent
D/WifiStateMachine(  912): Associated
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  912): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  912): Exit handleAssociatedWithEvent
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  912): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  912): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  912): This record is existed, only update it...
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  912): updateConnectedAP...
I/wpa_supplicant( 1182): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb79729f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1182):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1182): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ecbb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1182):    broadcast key
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1182): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1182): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1182): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1182): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1182): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=6
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1182): set send_ind_to_ndc = 0
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (1)+
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1182): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1182): EAPOL authentication completed successfully
I/wpa_supplicant( 1182): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
D/Tethering(  912): interfaceStatusChanged wlan0, true
D/WifiMonitor(  912): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/WifiStateMachine(  912): fetchFrequency(), freq = 2412
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  912): This record is existed, only update it...
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): mActiveDefaultNetwork: -1
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 3777): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3777): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/WifiNative-wlan0(  912): doBoolean: SET pno 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1182): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/DhcpStateMachine(  912): [StoppedState] Start DHCP
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiStateMachine(  912): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  912): acquireWL(434c0740): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 912 1000 null
,D/WifiStateMachine(  912): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 1
I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1182): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 1
I/wpa_supplicant( 1182): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  912):    returned null
E/WifiStateMachine(  912): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  912):    returned null
D/WifiP2pService(  912): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426071e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426071e8 target=com.android.internal.util.StateMachine$SmHandler }
,W/dalvikvm( 4469): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4469): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4469): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4469): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4469): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4469): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4469): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,W/dalvikvm( 4469): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1182): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
,W/dalvikvm( 4469): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  912):    returned true
,D/WifiStateMachine(  912): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
D/WifiP2pService(  912): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  912): releaseWL(434c0740): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1182): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/WifiStateMachine(  912): gateway: /192.168.1.1
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  912): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1182): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  912): VerifyingLinkState enter
D/WifiStateMachine(  912): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  912): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  912): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  912): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  912): WAN detection
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  912): Provision feature enable=false
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  912): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  912): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  912): default: teardown()
D/MDST    (  912): default: setTeardownRequested(true)
D/MDST    (  912): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 3777): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  912): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  912): syncGetConfiguredNetworks
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/MDST    (  912): default: setTeardownRequested(true)
D/ConnectivityService(  912): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  912): Unexpected mtu value: android.net.wifi.WifiStateTracker@4265a210
D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  912): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  912): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  912): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  912): handleConnectivityChange: resetting
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  912): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  912): acquireWL(44347b18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
D/WirelessDisplayService(  912): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  912):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,E/FbInjectorInitializer( 4469): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
I/QuickSettingWifi( 1113): receive.wifiConnect:true wifiAPname:NG700 elapse:3
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  912): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): releaseWL(44347b18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,W/fb4a(:<default>):StaticBindingVerifier( 4469): Verify
,D/wpa_supplicant( 1182): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1182): EAPOL: disable timer tick
,D/WifiService(  912): New client listening to asynchronous messages
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4469): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4469): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4469): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  912): killProcessQuiet, pid=3813
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 3813:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/AutoSetting( 1337): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1337/10055)
,I/ActivityManager(  912): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4536 uid=10079 gids={50079, 3003, 5012}
D/AutoSetting( 1337): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1337): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1337): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1337): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1337/10055)
,W/fb4a(:<default>):UserScope( 4469): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4469): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4469): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4536): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4536): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4536): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4536): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  912): Recipient 3813
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4550 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/Process (  912): killProcessQuiet, pid=4198
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.appDiedLocked:4131 
I/ActivityManager(  912): Killing 4198:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10079)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10079)
D/PMS     (  912): acquireWL(425fc5e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  912): Client connection lost with reason: 4
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10079)
,I/ActivityManager(  912): Recipient 4198
,D/PMS     (  912): acquireWL(4366d170): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450238203709 min interval config: 0 actual interval: 52438
D/PMS     (  912): releaseWL(425fc5e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checking schedule, now: 1450238256153 next: 1450238233685
,I/CheckinService( 2176): active receiver: enabled
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1450238199819
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/ActivityManager(  912): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4565 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  912): killProcessQuiet, pid=4011
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Killing 4011:com.google.android.talk/u0a111 (adj 15): empty #17
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  912): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4469): Grow heap (frag case) to 9.963MB for 84664-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4565): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4565): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4565): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4565): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4565): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/dalvikvm-heap( 4469): Grow heap (frag case) to 9.976MB for 28144-byte allocation
E/dalvikvm( 4469): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4469): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4469): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4469): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4469): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4469): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4469): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4469): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4469): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4469): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4469): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4469): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4469): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4469): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4469): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4469): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4469): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4469): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4469): Grow heap (frag case) to 10.044MB for 39954-byte allocation
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
I/ActivityManager(  912): Recipient 4011
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm-heap( 4469): Grow heap (frag case) to 10.121MB for 79892-byte allocation
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4565/10151)
,V/WebViewChromiumFactoryProvider( 4565): Binding Chromium to main looper Looper (main, tid 1) {41cd4180}
,I/LibraryLoader( 4565): Expected native library version number "",actual native library version number ""
,I/chromium( 4565): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4565): Initializing chromium process, renderers=0
,D/PMS     (  912): acquireWL(436651b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
,D/PMS     (  912): acquireWL(428854e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
,E/AudioManagerAndroid( 4565): BLUETOOTH permission is missing!
D/PMS     (  912): releaseWL(436651b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  912): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4595 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4565): Starting up...
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4565/10151)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4565/10151)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [2][0][0]
,W/dalvikvm( 4595): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4595): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
I/MultiDex( 4595): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4595): install
,D/Process (  912): killProcessQuiet, pid=4231
I/MultiDex( 4595): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4054/10160)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4054/10160)
,I/ActivityManager(  912): Killing 4231:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/dalvikvm-heap( 4469): Grow heap (frag case) to 10.284MB for 75760-byte allocation
I/MultiDex( 4595): loading existing secondary dex files
,I/MultiDex( 4595): load found 3 secondary dex files
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
I/MultiDex( 4595): install done
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Recipient 4231
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42945888 u0 ReceiverList{42938ca0 4469 com.facebook.katana/10027/u0 remote:425ba390}}
W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42945888 u0 ReceiverList{42938ca0 4469 com.facebook.katana/10027/u0 remote:425ba390}}
,D/AutoSetting( 1337): receiver - intent: android.intent.action.USER_PRESENT
W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{443d8ea8 u0 ReceiverList{44380dc8 4469 com.facebook.katana/10027/u0 remote:43d44898}}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/TetherSettings( 3777): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3777): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3777): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3777): Cust_ConnectToPC   : spcsc>false
D/        ( 3777): Cust_ConnectToPC   : IPT>true
D/        ( 3777): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3777): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3777): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3777): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3777): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1337): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,W/dalvikvm( 4595): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4595): VFY: unable to resolve instance field 36
,W/dalvikvm( 4595): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,I/PSReceiver( 3777): onReceive:android.intent.action.USER_PRESENT
,V/JNIHelp ( 4595): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/SmartNS_PSService( 3777): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3777): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3777):  defaultType:0
W/ContextImpl( 3777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,I/ActivityManager(  912): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4619 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  912): acquireWL(4330fc80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 4595): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  912): releaseWL(42864030): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  912): NetTransition Wakelock for ConnectedState released by timeout
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4469): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/PMS     (  912): releaseWL(4330fc80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: true
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4469): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  912): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  912): NoActiveNetworkState
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10076)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/PMS     (  912): acquireWL(434c5990): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/PMS     (  912): releaseWL(434c5990): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ContextImpl( 4469): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,V/Tethering(  912): bSetPropertyMultiRAB:false
,D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10079)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.musicenhancer (3871/10053)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (3835/10154)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/NetworkMonitor( 3835): type=WIFI subType= reason=null isConnected=true
,I/Tethering(  912): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  912): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  912): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  912): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  912): Found interface wlan0
,D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
,D/PMS     (  912): acquireWL(4283d730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/ContextImpl( 4619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/PMS     (  912): releaseWL(4283d730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/SmartSyncUtils( 4619): isEpsOn(), nState = 0
,D/PMS     (  912): acquireWL(43762148): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4619 1000 null
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
E/ExternalAccountType( 1325): Unsupported attribute readOnly
,W/dalvikvm( 4595): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4595): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,W/dalvikvm( 4595): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4595): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4595): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4595): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4595): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/PMS     (  912): releaseWL(43762148): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/SmartSyncUtils( 4619): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4619): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4619): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4619): getMobilePolicyEnabled, result = true
I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42834cb8
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 1
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42834cb8, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = CM36282 Proximity sensor
D/WifiService(  912): New client listening to asynchronous messages
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 0
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42834cb8, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42834cb8
D/ConnectivityService(  912): getActiveNetworkInfo called by  (2718/10021)
E/ActivityThread(  912): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4288de00 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4288de00 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  912): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  912): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  912): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  912): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  912): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  912): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  912): 	at dalvik.system.NativeStart.main(Native Method)
,D/Process (  912): killProcessQuiet, pid=4264
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Killing 4264:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/AutoSetting( 1337): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4536): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4536): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1337/10055)
I/ActivityManager(  912): Recipient 4264
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1337): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4565/10151)
,D/AutoSetting( 1337): service - onStartCommand() screen is off, don't request location
,I/WVCdm   (  374): Level3 Library Nov 20 2013 18:09:31
D/AutoSetting( 1337): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1337): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1337/10055)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/WVCdm   (  374): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
I/WVCdm   (  374): CdmEngine::OpenSession
,I/WVCdm   (  374): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  374): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4054/10160)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4054/10160)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450238203709 min interval config: 0 actual interval: 53171
,I/dalvikvm-heap( 4054): Grow heap (frag case) to 13.509MB for 1821008-byte allocation
D/PMS     (  912): acquireWL(43d59158): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(43d59158): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/NativeLibraryUtils( 4595): Install completed successfully. count=14 extracted=0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WearableService( 1220): callingUid 10029, callindPid: 1220
,E/MDM     ( 1220): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2176): Restart initialization of location
D/AuthorizationBluetoothService( 1353): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1353): Proximity feature is not enabled.
,D/WVCdm   (  374): PrepareKeyRequest: nonce=2656108293
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
D/PMS     (  912): acquireWL(426abaf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(426abaf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,I/WVCdm   (  374): CdmEngine::CloseSession
,I/WVCdm   (  374): CdmEngine::OpenSession
,I/WVCdm   (  374): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  374): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  374): PrepareKeyRequest: nonce=3446636057
,I/WVCdm   (  374): CdmEngine::CloseSession
,I/Adreno-EGL( 4595): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4595): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4595): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4595): Local Branch: 
I/Adreno-EGL( 4595): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4595): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4595):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4595): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4595): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4595): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4595): Local Branch: 
I/Adreno-EGL( 4595): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4595): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4595):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4595): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4595): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4595): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4595): Local Branch: 
I/Adreno-EGL( 4595): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4595): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4595):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (4595/10029)
,W/Settings( 4595): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4ecb +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 246
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2176): Sending checkin request (12208 bytes)
,I/jxcore-log( 4415): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4415): 
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  912): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b6ca +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  912): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  912): Find DNS Address www.htc.com/23.59.123.86
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=10 [19][2][0]
,W/fb4a(:<default>):UserScope( 4469): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4469): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2176): Checking schedule, now: 1450238258940 next: 1450761195935
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,I/CheckinService( 2176): Checking schedule, now: 1450238258968 next: 1450761195935
,I/CheckinService( 2176): active receiver: disabled
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1450238258973
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(4366d170): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/PMS     (  912): acquireWL(44353980): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1353): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1353): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    ( 1353): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1353): [NET] getaddrinfo-, 1
D/libc    ( 1353): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d574 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 213
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1353): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1353): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4469): Called registerBroadcastReceiver twice.
,D/libc    ( 1353): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/PMS     (  912): acquireWL(43940d30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4469/10027)
,D/PMS     (  912): releaseWL(44353980): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  912): handleInetConditionChange: starting a change hold
,D/PMS     (  912): releaseWL(43940d30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43722f90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
,D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
,D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(43722f90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(428854e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiStateMachine(  912): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  912): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1524): service - handleMessage() stop self
,D/AutoSetting( 1524): service - onDestroy() END
,D/AutoSetting( 1524): service - handleMessage() quit looper
,D/Process (  912): killProcessQuiet, pid=4280
,I/ActivityManager(  912): Killing 4280:com.htc.backup/1000 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 4280
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4565): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  912): killProcessQuiet, pid=4304
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4304:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4304
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  912): killProcessQuiet, pid=3871
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3871:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3871
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "sms"
I/ActivityManager(  912): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4680 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Launcher( 1270): Deferring update until onResume
,D/Launcher( 1270): waitUntilResume // bindAppsUpdated
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/AutoSetting( 1337): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/AutoSetting( 1337): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1337): service - requestNLP() NetworkLocationProvider not enabled
,I/Babel   ( 4680): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4680): MmsConfig.loadMmsSettings
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
,D/ConnectivityService(  912): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  912): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,W/dalvikvm( 4680): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4680): VFY: unable to resolve instance field 36
,W/dalvikvm( 4680): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4680): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  912): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4704 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4680, uid=10111, userID:0
,D/MessageFrequencyProvider( 4704): onCreate
,W/Settings( 4680): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 4704): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4704): GetPrviateResource
,V/GetPrviateResource( 4704): GetPrviateResource
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4680, uid=10111, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4680, uid=10111, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4680, uid=10111, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4680, uid=10111, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4680, uid=10111, userID:0
,D/MmsCustomizationProvider( 4704): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/PMS     (  912): acquireWL(42871588): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4680 10111 null
,I/Babel   ( 4680): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4680): MmsConfig.loadFromDatabase
,E/Babel   ( 4680): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4680): MmsConfig.loadFromResources
,E/Babel   ( 4680): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4680): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/[PluginManager]RegisterService( 1337): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1337): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2816): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  912): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  912): acquireWL(44295db8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4054): Grow heap (frag case) to 15.209MB for 1821008-byte allocation
,D/MessageCustFlag( 4704): sense_version=6.0
,D/BTAccessoryUtil( 4704): createReceiver
,D/BTAccessoryUtil( 4704): registerReceiver return intent = null
I/ProviderInstaller( 4680): Installed default security provider GmsCore_OpenSSL
D/MessageCustFlag( 4704): sku_id=99
,W/SystemReader( 4704): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  912): acquireWL(43cffe28): PARTIAL_WAKE_LOCK  AsyncService 0x1 4054 10160 null
D/Messaging( 4704): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4704): networkCode: 
D/MessageCustFlag( 4704): sku_id=99
D/MmsConfig( 4704): SIE smsPri: null
,D/MmsConfig( 4704): networkCode: 
D/PMS     (  912): releaseWL(42871588): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/HtcTelephonyCapability( 4704): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4704): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4704): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4704): Cannot find qct_8960_interface, use default value instead
,I/dalvikvm-heap( 4054): Grow heap (frag case) to 16.945MB for 1821008-byte allocation
D/PMS     (  912): releaseWL(43cffe28): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  912): Resuming delayed broadcast
,D/Process (  912): killProcessQuiet, pid=4251
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 4251:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  912): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  912): Recipient 4251
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Resuming delayed broadcast
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  912): Unable to load service info ResolveInfo{44391228 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
,I/IcingCorporaProvider( 2816): UpdateCorporaTask done [took 739 ms] updated apps [took 739 ms] 
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41d65d10 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,D/RemoteDisplayProvider(  912): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  912): start
,I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  912): applying state to connected service
D/PMS     (  912): acquireWL(43d77690): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(43d77690): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  912): applying state to connected service
,D/PMS     (  912): acquireWL(43e00e68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(4281c5e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(43e00e68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(4281c5e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42823248): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42823248): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41d65d10 -
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  912): releaseWL(44295db8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,D/PMS     (  912): acquireWL(4393d0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{43e42458: PendingIntentRecord{427dbfc0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=118242, Int=0
,D/PMS     (  912): releaseWL(4393d0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(4427b880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [8][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): acquireWL(433768b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): releaseWL(433768b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(4427b880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43defa80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(43defa80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43e3fdd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): acquireWL(43cedc98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43a967b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4704): mNeedToUpdateDate2 start
,D/MmsConfig( 4704): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4704): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4704): 
D/MmsAsyncWorkHandler( 4704): HM tk = 20001
D/ReportIndicatorCache( 4704): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4704): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ce14d8
,I/Messaging( 4704): mccmnc> 
,D/DraftCache( 4704): [DraftCache/1] DraftCache.constructor
D/DraftCache( 4704): [DraftCache/1] refresh
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4704): networkCode: 
,D/Messaging( 4704): ViewCache CreatePreloadOnlyConversationList
,I/VacuumService( 1220): Vacuum at: now=1450238268978 tag=VacuumService
,D/PMS     (  912): releaseWL(43e3fdd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1238):  phoneType = -1
D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/MessageCustFlag( 4704): sense_version=6.0
D/Jerry   ( 4704): start to preload cursor >>>>>>>
D/Messaging( 4704): mNeedToUpdateDate2: false
D/PhoneStorageUtil( 4704): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4704): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4704): createReceiver
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/TelephUtils( 1238): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,V/MmsProvider( 1238): Update uri=content://mms, match=0
,V/MmsProvider( 1238): selection=st=129 AND m_type!=134
D/Messaging( 4704): ViewCache CreatePreload
,D/Messaging( 4704): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1238): sku_id=99
,D/Cust_MMSMS( 4704): _has_set_default_values_2=true
,D/Messaging( 4704): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4704): TransactionService is going to be woken up.
,D/PMS     (  912): releaseWL(43cedc98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/DraftCache( 4704): [DraftCache/469] rebuildCache
D/MsgPreferenceUtils( 4704): def_index: 0
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MsgPreferenceUtils( 4704): globalIndex = 1
,D/PMS     (  912): acquireWL(430eaee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
D/Jerry   ( 1238): URI_DRAFT
V/TransactionService( 4704): 1-Creating TransactionService
D/MsgPreferenceUtils( 4704): phone state: true
D/MsgPreferenceUtils( 4704): sd state: false
,D/MsgPreferenceUtils( 4704): vIndex = 0
D/PMS     (  912): releaseWL(43a967b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
D/PMS     (  912): releaseWL(430eaee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/DraftCache( 4704): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4704): [DraftCache/469] rebuildCache time: 2
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
V/TransactionService( 4704): onStartCommand: 1
,D/MmsSystemEventReceiver( 4704): unRegisterForConnectionStateChanges
,D/MmsAsyncWorkHandler( 4704): 
D/MmsAsyncWorkHandler( 4704): HM tk = 20002
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/TransactionService( 4704): 4-Handling incoming message: { when=-2ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4704): Loading previous transactions.
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/MmsSmsV2Provider( 1238):  phoneType = -1
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PMS     (  912): acquireWL(4426cb98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1238): device_type: 1
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/AccFlag ( 1238): sku_id=99
D/TransactionService( 4704): Force set service start id to 1
V/TransactionService( 4704): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4704): unRegisterForConnectionStateChanges
V/TransactionService( 4704): Destroying TransactionService
D/TransactionService( 4704): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4704): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4704): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1238): sku_id=99
D/PMS     (  912): releaseWL(4426cb98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(4289c650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(4289c650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43e357f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(43e357f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42ded5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): acquireWL(43ed0118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(43ed0118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(442669d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42ded5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(439b28f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(439b28f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029),
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 4109 seconds from now (1450238269551)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  912): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1220): [NET] getaddrinfo-,err=8
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
,D/libc    ( 1220): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9536 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 287
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  912): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  912): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  912): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): releaseWL(442669d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43de7878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(43de7878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(434b7360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(434b7360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4680): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  912): acquireWL(4386f648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=129476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4386f648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43e0a6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  912): releaseWL(43e0a6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(43e03f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{43c03438: PendingIntentRecord{4252b4c0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134326, Int=0
,D/PMS     (  912): releaseWL(43e03f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/AutoSetting( 1337): service - mHandler: update timezone
,D/AutoSetting( 1524): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1524): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1524): service - onCreate()
,D/AutoSetting( 1524): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1524): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/DotMatrix( 1557): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1524): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1524): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1524): service - mHandler: update timezone
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1524): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1524): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1524): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1524): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41f85cb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 2 6 2 11
,D/AutoSetting( 1337): service - mHandler: update timezone
,D/AutoSetting( 1337): service - handleMessage() stop self
,D/AutoSetting( 1524): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1524): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1524): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1524): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1557): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1524): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1524): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1524): service - mHandler: update timezone
,D/AutoSetting( 1337): service - onDestroy() END
,D/AutoSetting( 1337): service - handleMessage() quit looper
,D/AutoSetting( 1524): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1524): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1524): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1524): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{421068f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 3 8 2 11
,D/PMS     (  912): acquireWL(43e9e1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{420d82b0: PendingIntentRecord{42415298 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141089, Int=0
,D/GpsLocationProvider(  912): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  912): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  912): acquireWL(43e97e88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(43e9e1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  912): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ba71 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo_proxy-, success
,I/global  (  912): call createSocket() return a new socket.
D/libc    (  912): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  912): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  912): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  912): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  912):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  912): killProcessQuiet, pid=4335
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4335:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4335
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): releaseWL(43e97e88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{43e684f0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  912): acquireWL(43d24b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(43d24b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/ClearcutLoggerApiImpl( 1353): disconnect managed GoogleApiClient
,D/AutoSetting( 1524): service - handleMessage() stop self
,D/AutoSetting( 1524): service - handleMessage() quit looper
,D/AutoSetting( 1524): service - onDestroy() END
,I/ActivityManager(  912): Killing 4350:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  912): killProcessQuiet, pid=4350
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 4350
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(43b93578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10027}
,V/AlarmManager(  912): sending alarm PendingIntent{4377d7b0: PendingIntentRecord{43c36468 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=169676, Int=0
,D/PMS     (  912): releaseWL(43b93578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
,D/PMS     (  912): acquireWL(43b8cef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=189476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43b8cef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43b78cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(43b78cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(438897d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
,D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  912): releaseWL(438897d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(430e51e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=249476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(430e51e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(4286b0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(4286b0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(426d7580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
,D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/BatteryService(  912): n_update end
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(426d7580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(4252b3f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=309476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4252b3f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(420f61b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(420f61b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4415): Connected to the server!
I/jxcore-log( 4415): 
,I/chromium( 4415): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  912): acquireWL(4258d5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(4258d5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(43def0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=369475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1270): Grow heap (frag case) to 12.644MB for 50416-byte allocation
,D/PMS     (  912): releaseWL(43def0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(429077b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(429077b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(42799bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=429476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42799bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(425f9768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(425f9768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  912): runPSCheck
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): Checking...
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42711678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42711678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(42618120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=489476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42618120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42224090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42224090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(427bbb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/PMS     (  912): releaseWL(427bbb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(42e5bb80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=549476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42e5bb80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42753d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42753d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
,I/HtcPowerSaver(  912): >> updateStatus
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43b92ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=609476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43b92ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42879200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42879200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1238): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1238): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1238): sku_id=99
,D/ContactMessageStore( 1238): start background delete task...
,D/ContactMessageStore( 1238): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
,D/Process (  912): killProcessQuiet, pid=3981
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3981:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3981
,D/PMS     (  912): acquireWL(43b9b2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43b9b2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(427de5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=669476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1270): Grow heap (frag case) to 12.644MB for 50416-byte allocation
,D/PMS     (  912): releaseWL(427de5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42606078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42606078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(4259b358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(4259b358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1113): closing low battery warning: level=100
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43375ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=729476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43375ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(427fbbe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(427fbbe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(426e31b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(426e31b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(4282a750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=789475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4282a750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(4260f618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): releaseWL(4260f618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43d77db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=849476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43d77db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(4282f370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): releaseWL(4282f370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(44005ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(44005ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42697238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=909475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42697238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(4278f4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(4278f4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(43846408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  912): updateBatteryInfo,
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
,I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(43846408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(443a2148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=969475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(443a2148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43925678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43925678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(43658200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
V/AlarmManager(  912): sending alarm PendingIntent{41f79a68: PendingIntentRecord{426649c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=778608, Int=0
,D/ConnectivityService(  912): Sampling interval elapsed, updating statistics ..
,D/PMS     (  912): acquireWL(43936260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43936260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/ConnectivityService(  912): Done.
,D/ConnectivityService(  912): Setting timer for 720seconds
,I/ActivityManager(  912): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4815 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  912): sending alarm PendingIntent{427bf228: PendingIntentRecord{428596a8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450238362223, Int=10800000
,V/AlarmManager(  912): sending alarm PendingIntent{4368d518: PendingIntentRecord{41df8d00 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450238517870, Int=1800000
,V/AlarmManager(  912): sending alarm PendingIntent{4258a7c8: PendingIntentRecord{425a2888 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450239082527, Int=900000
,V/AlarmManager(  912): sending alarm PendingIntent{43eb1548: PendingIntentRecord{428666d8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450239156773, Int=0
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): acquireWL(428092e8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,D/PMS     (  912): acquireWL(42857750): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(428092e8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4619): call getInstance()
,D/SmartSyncUtils( 4619): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4619): MY_DEBUG = false
,I/EventLogService( 2176): Aggregate from 1450238256203 (log), 1450236717822 (data)
D/PMS     (  912): releaseWL(43658200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  912): acquireWL(43bb62f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4619 1000 null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/SmartSyncScreenOnOffTimeReceiver( 4619): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4619): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4619): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4619): SettingOnTime = 1450245600000, randomSettingOnTime = 1450242058000
,D/SmartSyncScreenOnOffTimeReceiver( 4619): SettingOffTime = 1450317600000, randomSettingOffTime = 1450323141000
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.aurora (4815/10049)
D/SmartSyncScreenOnOffTimeReceiver( 4619): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4619): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4619): bNightModeTurnOffOnce = false
W/BatSI   (  912): Couldn't get kernel wake lock stats
D/PMS     (  912): acquireWL(426480c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
V/AlarmManager(  912): sending alarm PendingIntent{434cafb8: PendingIntentRecord{43ec69d0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450239156889, Int=0
W/ContextImpl( 4619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  912): releaseWL(43bb62f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4619): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4619): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  912): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4619): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 4619): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  912): getProviders()=[gps, network]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
I/ActivityManager(  912): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
,D/LocationManagerService(  912): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  912): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 4619): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 4619): isCharging status = 5
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/SmartSyncDataLinkTurnOffService( 4619): turnOffWifi ui setting = true
,D/WifiStateMachine(  912): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4619): isWifiHotSpotEnabled = false
I/ActivityManager(  912): Resuming delayed broadcast
D/PMS     (  912): releaseWL(426480c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): releaseWL(42857750): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
D/SmartSyncUtils( 4619): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4619): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 4619): turnOffWifi bWifiConnected = true
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4619/1000)
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/Process (  912): killProcessQuiet, pid=4386
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4386:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4386
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(4386a890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{425eb4e0: PendingIntentRecord{4289f2f0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1008774, Int=0
,D/PMS     (  912): acquireWL(43dc79f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(43dc79f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43b5bc90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(4386a890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=7 [246][19][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): acquireWL(44275630): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
,D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  912): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(44275630): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43dfce40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
D/PMS     (  912): releaseWL(43b5bc90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/PMS     (  912): acquireWL(43ec8c08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(43ec8c08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1220): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
,D/libc    ( 1220): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =40f2 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11542
D/libc    (  363): [NET]res_nsend:resplen=45
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  912): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=44 [9][4][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0],
,D/libc    ( 1220): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,W/PhenotypeConfigurator( 1220): Server returned 404
,D/PMS     (  912): releaseWL(43dfce40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(4435f560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
,D/PMS     (  912): releaseWL(4435f560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(442fa530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1029475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1270): Grow heap (frag case) to 12.645MB for 50416-byte allocation
,D/PMS     (  912): releaseWL(442fa530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(442f6850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(442f6850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(442844b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): releaseWL(442844b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(44004d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1089476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(44004d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43eac5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43eac5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(43ea52f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderNotification, total:1
,D/HeadsetPhoneState( 1624): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
V/NotificationService(  912): batLight: plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c80000
D/qdlights(  912): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/HtcPowerSaver(  912): updateBatteryInfo
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  912): releaseWL(43ea52f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=98
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,W/ContextImpl( 4619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3777): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3777): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3777): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3777): Cust_ConnectToPC   : spcsc>false
D/        ( 3777): Cust_ConnectToPC   : IPT>true
D/        ( 3777): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3777): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3777): Index of the first 1 = -1
W/Settings( 3777): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3777): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3777): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3777): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3777): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3777): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43e1f8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1149475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43e1f8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43e03678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43e03678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=98
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43d7ef58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{43e953b8: PendingIntentRecord{4370b0d8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450239336949, Int=0
,W/ContextImpl( 4619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  912): releaseWL(43d7ef58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 4619): turnOffWifi ui setting = true
,D/WifiStateMachine(  912): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4619): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4619): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4619): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4619): turnOffWifi bWifiConnected = true
D/LocationManagerService(  912): getProviders()=[gps, network]
D/LocationManagerService(  912): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  912): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 4619): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4619/1000)
D/SmartSyncUtils( 4619): isCharging status = 2
,D/PMS     (  912): acquireWL(43d56e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(43d56e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=98
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43c32c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1209475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43c32c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43c32900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43c32900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  912): acquireWL(43c12f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1269476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1270): Grow heap (frag case) to 12.645MB for 50416-byte allocation
D/PMS     (  912): releaseWL(43c12f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43bf6d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43bf6d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(43b8cce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=99
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(43b8cce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42627fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1329475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42627fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(420de348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(420de348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(41ffd670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1389475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(41ffd670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(439d0b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(439d0b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42876958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=99
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(42876958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(4231dc30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1449476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4231dc30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43b5fc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43b5fc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  912): updateBatteryInfo
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=99
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(426b8f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
I/BatteryService(  912): n_update end
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  912): releaseWL(426b8f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderNotification, total:0
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1624): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 4619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,D/TetherSettings( 3777): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3777): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3777): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3777): Cust_ConnectToPC   : spcsc>false
D/        ( 3777): Cust_ConnectToPC   : IPT>true
D/        ( 3777): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3777): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3777): Index of the first 1 = -1
W/ContextImpl( 3777): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3777): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3777): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3777): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3777): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43d6a7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1509475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43d6a7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(434b6d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(434b6d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(4273acf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(4273acf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42802068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1569475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42802068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42703508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42703508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(4252a008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1629475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4252a008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(439b9110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(439b9110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(427e8148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1689475, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1270): Grow heap (frag case) to 12.645MB for 50416-byte allocation
,D/PMS     (  912): releaseWL(427e8148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(4267f0a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(4267f0a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(424b0338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1749476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(424b0338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(436bdc30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(436bdc30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/PMS     (  912): acquireWL(42827c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1809476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42827c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(425dd260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(425dd260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  912): acquireWL(42949c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41cd2dd8: PendingIntentRecord{424e85d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1869476, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  912): Prepared write state in 49ms
,I/dalvikvm-heap( 1270): Grow heap (frag case) to 12.645MB for 50416-byte allocation
,D/PMS     (  912): releaseWL(42949c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  912): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-03-40.bin
,D/PMS     (  912): acquireWL(427938b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(427938b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1800000ms),D/PMS     (  912): acquireWL(4258a710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
D/ConnectivityService(  912): Sampling interval elapsed, updating statistics ..
D/Process (  912): killProcessQuiet, pid=4565
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  912): killProcessQuiet, pid=4550
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  912): Killing 4565:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
V/AlarmManager(  912): sending alarm PendingIntent{41f79a68: PendingIntentRecord{426649c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1726278, Int=0
I/ActivityManager(  912): Killing 4550:com.android.chrome/u0a96 (adj 15): empty for 1802s
D/Process (  912): killProcessQuiet, pid=4536
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  912): killProcessQuiet, pid=3835
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  912): Killing 4536:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
I/ActivityManager(  912): Killing 3835:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
V/AlarmManager(  912): sending alarm PendingIntent{42215390: PendingIntentRecord{427b02d8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820621, Int=1800000
V/AlarmManager(  912): sending alarm PendingIntent{42772890: PendingIntentRecord{42955300 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1845544, Int=0
D/PMS     (  912): acquireWL(4252f4f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
V/AlarmManager(  912): sending alarm PendingIntent{42157130: PendingIntentRecord{4289f2f0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1908855, Int=0
V/AlarmManager(  912): sending alarm PendingIntent{4258a7c8: PendingIntentRecord{425a2888 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450239982527, Int=900000
D/ConnectivityService(  912): Done.
D/ConnectivityService(  912): Setting timer for 720seconds
I/ActivityManager(  912): Recipient 4536
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Recipient 4550
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  912): releaseWL(4252f4f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  912): acquireWL(43e78368): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
D/LocationManagerService(  912): getAllProviders()=[passive, gps, network]
D/PMS     (  912): releaseWL(43e78368): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  912): releaseWL(4258a710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BatSI   (  912): Couldn't get kernel wake lock stats
D/PMS     (  912): acquireWL(43bf8068): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: starting a change hold
V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1353/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023885
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024062
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024126
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024132
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025596
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025616
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028517
I/ActivityManager(  912): Recipient 4565
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  912): releaseWL(43bf8068): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Recipient 3835
D/MediaRouterService(  912): Client com.google.android.music (pid 3835): Died!
W/BatSI   (  912): Couldn't get kernel wake lock stats
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1353): [NET] getaddrinfo-, 1
D/libc    ( 1353): [NET] getaddrinfo_proxy+
V/NativeCrypto( 1353): SSL shutdown failed: ssl=0x5cbe5460: I/O error during system call, Connection timed out
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4911 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1353): [NET] getaddrinfo_proxy-, success
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1353): [NET] getaddrinfo-,err=8
W/BatSI   (  912): Couldn't get kernel wake lock stats
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1353): [NET] getaddrinfo-,err=8
W/BatSI   (  912): Couldn't get kernel wake lock stats
E/cutils-trace( 4861): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4861): ====startRecUseTime====
D/htc.customization.log.level( 4861):  is 
W/CustomizationLogLevel( 4861): Level value is invalid, use default level 2
D/ConnectivityService(  912): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=18 [183][33][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/CustomizationManager( 4861):  Read ACC file spent 0.117 (s)
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4861): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4861): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4861): Parsing tag category name = system
I/CustomizationCIDLoader( 4861): Parsing tag category name = application
I/CustomizationCIDLoader( 4861): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4861): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4861): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4861): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4861): Parsing tag category name = Settings
D/CustomizationManager( 4861):  Read CID file spent 0.175 (s)
D/CustomizationManager( 4861):  All configurations done spent 0.176 (s)
W/HtcNativeFlag( 4861): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4861): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4861): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4861): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  912): deletePackageAsUser: pkg=com.test.thalitest, pid=4861, uid=2000 user=0
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  912): killProcessQuiet, pid=4415
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  912): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  912): Killing 4415:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  912):   Force finishing activity ActivityRecord{43d3c8d0 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  912): Copying FileAsset 0x6de0f9b0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  912): WIN DEATH: Window{43375690 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  912): Client connection lost with reason: 4
D/PMS     (  912): acquireWL(43e773c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
W/PackageSettings(  912): Skipping PackageSetting{42347a68 com.example.hello/10397} due to missing metadata
W/InputMethodManagerService(  912): Got RemoteException sending setActive(false) notification to pid 4415 uid 10389
D/PMS     (  912): releaseWL(43e773c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912): BroadcastReceiver::onReceive+
W/Binder  ( 1205): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1205): java.lang.NullPointerException
W/Binder  ( 1205): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1205): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1205): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1205): 	at dalvik.system.NativeStart.run(Native Method)
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
I/HtcPowerSaver(  912): << updateStatus
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
D/PMS     (  912): acquireWL(442f7ec8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/PMS     (  912): releaseWL(442f7ec8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
D/VoicemailCleanupService( 1295): Cleaning up data for package: com.test.thalitest
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1337): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/[PluginManager]RegisterService( 1337): handle notify Blinkfeed plugin client changed
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
E/ExternalAccountType( 1325): Unsupported attribute readOnly
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2816): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  912): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4886 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2816): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2816): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64525068
W/dalvikvm( 2816): threadid=14: thread exiting with uncaught exception (group=0x418a0e30)
E/AndroidRuntime( 2816): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2816): Process: com.google.android.googlequicksearchbox:search, PID: 2816
E/AndroidRuntime( 2816): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2816): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2816): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2816): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2816): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2816): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2816): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2816): 	at cid.d(PG:186)
E/AndroidRuntime( 2816): 	at clo.g(PG:594)
E/AndroidRuntime( 2816): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2816): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2816): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2816): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2816): 	at clr.tL(PG:827)
E/AndroidRuntime( 2816): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2816): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2816): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2816): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2816): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  912): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2816): killProcess, pid=2816
D/Process ( 2816): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
I/ActivityManager(  912): Recipient 2816
I/ActivityManager(  912): Process com.google.android.googlequicksearchbox:search (pid 2816) has died.
D/MediaRouterService(  912): Client com.google.android.googlequicksearchbox (pid 2816): Died!
D/WifiService(  912): Client connection lost with reason: 4
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
I/InputMethodManagerService(  912): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4886): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4886): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4886): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4886): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4886): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4886): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4886): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4886): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4886): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4886): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4886): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4886): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4886): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4886): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4886): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4886): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4886): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4886): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4886): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4886): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4886): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4886): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4886): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4886): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4886): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4886): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4886): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4886): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4886): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4886): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4886): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4886): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4886): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4886): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4886): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4886): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4886): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4886): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4886): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4886): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4886): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4886): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4886): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4886): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4886): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4886): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4886): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4886): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4886): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4886): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4886): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4886): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4886): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4886): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4886): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4886): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4886): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4886): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4886): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4886): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4886): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4886): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4886): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4886): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4886): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4886): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4886): threadid=11: thread exiting with uncaught exception (group=0x418a0e30)
E/ActivityManager(  912): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4886): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4886): Process: com.google.android.apps.docs, PID: 4886
E/AndroidRuntime( 4886): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4886): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4886): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4886): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4886): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4886): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4886): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4886): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
I/ActivityManager(  912): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4903 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4886): killProcess, pid=4886
D/Process ( 4886): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  912): Recipient 4886
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.google.android.apps.docs (pid 4886) has died.
W/ContextImpl( 4903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4903): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4903): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4903): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4903): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4903): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4903): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4903): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4903): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4903): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4903): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4903): threadid=10: thread exiting with uncaught exception (group=0x418a0e30)
E/AndroidRuntime( 4903): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4903): Process: com.android.keychain, PID: 4903
E/AndroidRuntime( 4903): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4903): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4903): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4903): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4903): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4903): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4903): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4903): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4903): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  912): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4916 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
W/PackageManager(  912): Unable to load service info ResolveInfo{42750ff0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
E/ActivityManager(  912): App crashed! Process: com.android.keychain
D/ErrorReport(  912): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4903): killProcess, pid=4903
D/Process ( 4903): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  912): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  912): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450240061715.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  912): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  912): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  912): 	... 4 more
I/ActivityManager(  912): Recipient 4903
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.android.keychain (pid 4903) has died.
W/ActivityManager(  912): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10463ms
D/AppTag  ( 4916): getInstance(Context context)
D/AppTag  ( 4916): getInstance(Context context)
D/AppTag  ( 4916): onCreate()
D/PMS     (  912): acquireWL(442b36a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4054 10160 null
D/PMS     (  912): releaseWL(442b36a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4079): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2176): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2176): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  912): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65cd58c8
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x656d4530
W/dalvikvm( 2176): threadid=48: thread exiting with uncaught exception (group=0x418a0e30)
E/DriveAsyncService( 2176): disk I/O error (code 3850)
E/DriveAsyncService( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2176): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  912): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2176): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2176): Process: com.google.android.gms, PID: 2176
E/AndroidRuntime( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2176): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2176): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2176): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2176): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 2176): killProcess, pid=2176
D/Process ( 2176): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
I/ActivityManager(  912): Recipient 2176
I/ActivityManager(  912): Process com.google.android.gms (pid 2176) has died.
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  912): Client connection lost with reason: 4
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41d65d10 +
I/Prism.WidgetManager( 1270): onLoadItems() +
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10095ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10094ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10093ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10092ms
I/ActivityManager(  912): Resuming delayed broadcast

```
