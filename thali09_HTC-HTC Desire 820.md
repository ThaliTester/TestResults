#### Test 552541413820a6d_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  911): setLight #0: color=#24
V/LightsService(  911): setLight #0: color=#21
V/LightsService(  911): setLight #0: color=#17
,V/LightsService(  911): setLight #0: color=#14
I/ActivityManager(  911): Waited long enough for: ServiceRecord{428ccd80 u0 com.htc.htclocationservice/.AutoSettingService}
--------- beginning of /dev/log/main
E/cutils-trace( 4499): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4499): ====startRecUseTime====
D/htc.customization.log.level( 4499):  is 
W/CustomizationLogLevel( 4499): Level value is invalid, use default level 2
D/CustomizationManager( 4499):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4499): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4499): Parsing tag category name = system
I/CustomizationCIDLoader( 4499): Parsing tag category name = application
I/CustomizationCIDLoader( 4499): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4499): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4499): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4499): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4499): Parsing tag category name = Settings
D/CustomizationManager( 4499):  Read CID file spent 0.103 (s)
D/CustomizationManager( 4499):  All configurations done spent 0.103 (s)
W/HtcNativeFlag( 4499): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4499): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4499): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4499): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4499
D/PMS     (  911): acquireHCC(43ee0298): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(43d1fb58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
W/asset   (  911): Copying FileAsset 0x6c6caad8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1144319128
I/FeedHostManager( 1278): [onPause]
I/FeedProviderManager( 1278): onPause
I/FeedHostManager( 1278): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ee8530
I/SocialFeedProvider( 1278): +onPause
I/SocialFeedProvider( 1278): -onPause
D/PMS     (  911): acquireWL(43a638f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/ActivityManager(  911): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4510 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1278): [trimMemory] 20
W/asset   ( 4510): Copying FileAsset 0x5c7a4428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4510): Binding Chromium to main looper Looper (main, tid 1) {41da24a8}
I/LibraryLoader( 4510): Expected native library version number "",actual native library version number ""
I/chromium( 4510): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4510): Initializing chromium process, renderers=0
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427e1c90:true
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4510): 1104903904: getState(). Returning 12
D/PMS     (  911): acquireWL(43a4ded8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): acquireWL(43a4de68): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): releaseWL(43a4ded8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4510): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4510): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4510): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4510): Local Branch: 
I/Adreno-EGL( 4510): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4510): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4510):                  aa63bbd948f41d15fc72f585e
W/chromium( 4510): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4510): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4510): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4510): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4510): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4510): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4510): CordovaWebView is running on device made by: HTC
,W/AwContents( 4510): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  911): Disable input method client, pid=1278
W/ResourceType( 4510): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4510): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41de9590, mServedView=org.apache.cordova.engine.SystemWebView{41daf1f8 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  911): Displayed com.test.thalitest/.MainActivity: +291ms
I/InputMethodManagerService(  911): Enable input method client, pid=4510
W/AwContents( 4510): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  911): releaseWL(43a638f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
D/JsMessageQueue( 4510): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4510): JniHelper::setJavaVM(0x41961010), pthread_self() = 1663297664
D/JX-Cordova( 4510): jxcore cordova android initializing
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.626MB for 96598-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.706MB for 144892-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.821MB for 217334-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 11.998MB for 325996-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 12.272MB for 488990-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 13.290MB for 1100216-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 14.175MB for 1650320-byte allocation
,W/PluginManager( 4510): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 15.518MB for 2475476-byte allocation
,D/PMS     (  911): acquireWL(43394fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=100349, Int=0
,D/PMS     (  911): releaseWL(43394fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1119): now=1452109920043 next=59957
W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
D/PMS     (  911): releaseHCC(43ee0298): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
D/PMS     (  911): releaseHCC(43d1fb58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 17.567MB for 3713210-byte allocation
,W/jxcore-log( 4510): Initializing JXcore engine
,W/jxcore-log( 4510): JXcore engine is ready
,W/jxcore-log( 4510): Starting JXcore engine
,W/jxcore-log( 4510): Platform android
W/jxcore-log( 4510): 
,W/jxcore-log( 4510): Process ARCH arm
W/jxcore-log( 4510): 
,I/jxcore-log( 4510): JXcore Cordova bridge is ready!
I/jxcore-log( 4510): 
,W/jxcore-log( 4510): JXcore engine is started
,I/chromium( 4510): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/PMS     (  911): releaseWL(43a4de68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/SensorManager(  911): mEventCount = 1050
,I/jxcore-log( 4510): Toggling radios to true
I/jxcore-log( 4510): 
,D/BluetoothAdapter( 4510): enable(): BT is already enabled..!
,D/WifiManager( 4510): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  911): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  911): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  911): Settings:Agentvalue: 2
W/Settings:Agent(  911): >> traceCallingStack()
W/Settings:Agent(  911): Process.myPid(): 911
W/Settings:Agent(  911): Process.myTid(): 1102
W/Settings:Agent(  911): Process.myUid(): 1000
W/Settings:Agent(  911): 
W/Settings:Agent(  911): 
,W/System.err(  911): java.lang.Throwable: stack dump
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
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  911): 
,W/Settings:Agent(  911): << traceCallingStack(): 1(ms)
D/WifiManager( 4510): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  911): setWifiEnabled: true pid=4510, uid=10389
E/WifiService(  911): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  911): New client listening to asynchronous messages
I/WifiService(  911): isSprintWifiRestricted(): false
I/WifiService(  911): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  911): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiManager( 4510): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  911): doBoolean: DISCONNECT
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): TDLS: Tear down peers
I/wpa_supplicant( 1166): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4510): Radios toggled
I/jxcore-log( 4510): 
D/BluetoothManagerService(  911): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4510): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4510): 
I/jxcore-log( 4510): Perf Test app loaded loaded
I/jxcore-log( 4510): 
I/jxcore-log( 4510): check test folder
I/jxcore-log( 4510): 
I/jxcore-log( 4510): found test : ./testFindPeers.js
I/jxcore-log( 4510): 
,I/jxcore-log( 4510): found test : ./testSendData.js
I/jxcore-log( 4510): 
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1166): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1166): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  911): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  911): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  911): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1166): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7e57bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1166):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1166): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1166): State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1166): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  911):    returned true
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiPerfLock(  911): release()
,D/WifiStateMachine(  911): PerfLock released for exiting ConnectedState
,D/ConnectivityService(  911): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/Tethering(  911): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2,
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  911):    returned true
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/PMS     (  911): acquireWL(421b38d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 911 1000 null
D/WifiP2pService(  911): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DhcpStateMachine(  911): [RunningState] Stop DHCP
D/WifiNative-wlan0(  911): doBoolean: RECONNECT
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): Fast associate: Old scan results
I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20623 mDataStallAlarmIntent=PendingIntent{4290c278: PendingIntentRecord{426ffb68 android broadcastIntent}}
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  911):    returned true
D/WifiStateMachine(  911): Enter handleNetworkDisconnect
D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  911):    returned true
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WISPrService( 3830): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/UsbnetStateTracker(  911): isAvailable+-
D/UsbnetStateTracker(  911): reconnect
,D/UsbnetStateTracker(  911): isAvailable+-
D/WifiP2pService(  911): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  911): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  911): default: reconnect()
D/MDST    (  911): default: setTeardownRequested(false)
D/MDST    (  911): default: setEnableApn apnType =default , enable=true
D/WifiService(  911): New client listening to asynchronous messages
D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  911): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  911): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3830): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  911): Exit handleNetworkDisconnect
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  911): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): handleConnectivityChange: resetting
D/ConnectivityService(  911): resetConnections(wlan0, 3)
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,V/NativeCrypto( 1363): Read error: ssl=0x660db968: I/O error during system call, Connection timed out
,V/NativeCrypto( 1363): SSL shutdown failed: ssl=0x660db968: I/O error during system call, Broken pipe
D/libc    (  364): [NET] entry_id:4   entry:0xb86a4cd8  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb86a02e8  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb86a4db8  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb869bc20  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb86a01c8  removed 
,D/libc    (  364): [NET] entry_id:1   entry:0xb86a4f70  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb86a0398  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb86a0458  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb86a08d0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/PMS     (  911): acquireWL(42887548): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): flush DNS cache for net 1(wlan0)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(4447da70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
D/ConnectivityService(  911): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
,D/ConnectivityService(  911): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiStateMachine(  911): startScan Pid: 911 Uid 1000
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiNative-wlan0(  911): doBoolean: SCAN
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  911):    returned false
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  911): reportInetCondition for net -1, percentage: 0 by  (1363/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/BatSI   (  911): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  911): releaseWL(42887548): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/WISPrService( 3830): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3830): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  911): mActiveDefaultNetwork: -1
,D/ConnectivityService(  911): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  911): releaseWL(4447da70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/Choreographer( 4510): Skipped 85 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4510): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: false
V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  911): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/CaptivePortalTracker(  911): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  911): NoActiveNetworkState
D/Tethering(  911): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  911): bSetPropertyMultiRAB:false
D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  911): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  911): ipv4Default null
I/Tethering(  911): No IPv4 upstream interface, giving up.
,D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1278): [onReceive] WIFI(1): DISCONNECTED
I/ActivityManager(  911): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4564 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(42829f60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): releaseWL(42829f60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4360/10100)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1278/10076)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4360/10100)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,I/MusicStore( 4564): Database version: 95
,W/ContextImpl( 4564): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4564): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4564, uid=10154, userID:0
,D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
,D/MediaRouterService(  911): Client com.google.android.music (pid 4564): Registered
,I/MediaRouter( 4564): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.music (4564/10154)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1976/10021)
,I/ActivityManager(  911): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4584 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4564): getSelectedRoute
,I/NetworkMonitor( 4564): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (4564/10154)
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4564, uid=10154, userID:0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(43909108): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/Process (  911): killProcessQuiet, pid=4275
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Killing 4275:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/ACRA    ( 4584): ACRA is enabled for com.facebook.katana, intializing...
D/PMS     (  911): releaseWL(43909108): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ACRA    ( 4584): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4584): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4275
,W/SystemClassLoaderAdder( 4584): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4584): Preparing secondary program dexes.
V/DexLibLoader( 4584): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4584): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4584): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4584): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4584): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4584): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4584): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4584): Dex already copied
D/OdexVerifier( 4584): Odex verification is skipped.
,V/DexLibLoader( 4584): Creating class loader,
V/DexLibLoader( 4584): Finished creating class loader,
V/DexLibLoader( 4584): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4584): Dex already copied
D/OdexVerifier( 4584): Odex verification is skipped.
,V/DexLibLoader( 4584): Creating class loader
,V/DexLibLoader( 4584): Finished creating class loader,
V/DexLibLoader( 4584): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4584): Dex already copied
D/OdexVerifier( 4584): Odex verification is skipped.
,V/DexLibLoader( 4584): Creating class loader
,V/DexLibLoader( 4584): Finished creating class loader
V/DexLibLoader( 4584): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4584): Dex already copied
D/OdexVerifier( 4584): Odex verification is skipped.
,V/DexLibLoader( 4584): Creating class loader
,V/DexLibLoader( 4584): Finished creating class loader
,V/DexLibLoader( 4584): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4584): DexLibLoader.ensureDexLoaded took 20 ms
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  911): Couldn't get kernel wake lock stats
V/LightsService(  911): setLight #2: color=#0
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@424a6120
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@424a6120, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42211d68
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@41eba0d0
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,W/PMS     (  911): mWirelessDisplayManager is null
D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/dalvikvm( 4584): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4584): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4584): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4584): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4584): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4584): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4584): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1166): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1166): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1166): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1166): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1166): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 3
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 1
I/wpa_supplicant( 1166): wpa_s->is_screen_on 1
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): selected network = 2
D/wpa_supplicant( 1166): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7e594e8  current_ssid=0x0
D/wpa_supplicant( 1166): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1166): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1166): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1166): check if in concurrent case
,I/wpa_supplicant( 1166): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1166): RSN: PMKSA cache search - network_ctx=0xb7e594e8 try_opportunistic=0
D/wpa_supplicant( 1166): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1166): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1166): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1166): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1166): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1166): nl80211: Unsubscribe mgmt frames handle 0xb7e58718 (mode change)
D/wpa_supplicant( 1166): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7e58718
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718,
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718,
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb7e58718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1166):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1166):   * freq=2412
D/wpa_supplicant( 1166):   * Auth Type 0,
D/wpa_supplicant( 1166):   * WPA Versions 0x2
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1166): nl80211: Connect request send successfully
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987",
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1166): reply (489) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-47
I/wpa_supplicant( 1166): tsf=0000000104961042
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-55
I/wpa_supplicant( 1166): tsf=0000000104961060
,I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-55
I/wpa_supplicant( 1166): tsf=0000000104961055
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-76
I/wpa_supplicant( 1166): tsf=0000000104961065
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ####
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiManager( 1228): getScanResults enter 
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 104961042, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 104961060, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 104961055, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 104961065, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
D/BatSI   (  911): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 316ms
,D/NfcService( 1261): ScreenObserver: OFF
D/NfcService( 1261): applyRouting - 0
W/ResourceType( 4510): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4510): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41daf1f8 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
D/PMS     (  911): OOBE c monitor 11
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
I/InputMethodManagerService(  911): Disable input method client, pid=4510
,D/NfcService( 1261): applyRouting -2
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  911): acquireWL(43e34608): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
D/PMS     (  911): releaseWL(43e34608): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43fe7d20)
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
D/PMN     (  911): wakingUp
D/PMS     (  911): acquireWL(442ef6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
I/WindowManager(  911): No lock screen! windowToken=null
D/PMS     (  911): releaseWL(442ef6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  911): onScreenOn
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  911): doBoolean: SET pno 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:On
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
D/MtpService( 1976): [MTP][onReceive]+android.intent.action.USER_PRESENT
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  911):    returned true
,D/MtpService( 1976): [MTP][onReceive]-
,D/NfcService( 1261): applyRouting - 0
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): CTRL_IFACE SET 'pno'='0'
D/NfcService( 1261): applyRouting -2
,D/WifiNative-wlan0(  911):    returned true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
D/PMS     (  911): acquireWL(43a4c7e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/PMS     (  911): releaseWL(43a4c7e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
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
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1119): stop update clock
D/NetworkPolicy(  911): updateScreenOn: false
,D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1166): nl80211: Connect event
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1166): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1166): Add randomness: count=11 entropy=4
I/wpa_supplicant( 1166): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1166): TDLS: Remove peers on association
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1166): EAPOL: enable timer tick
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1166): getPrivFuncNum +	
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1166): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  911): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  911): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1166): Get randomness: len=32 entropy=5
D/HTCRequest(  911): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  911): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  911): handleAssociatedWit,hEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  911): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  911): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  911): Enter handleAssociatedWithEvent
D/WifiStateMachine(  911): Associated
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  911): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  911): Exit handleAssociatedWithEvent
D/WifiStateMachine(  911): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
D/Tethering(  911): interfaceStatusChanged wlan0, true
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  911): This record is existed, only update it...
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
I/wpa_supplicant( 1166): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7e589f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1166):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1166): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fb3b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1166):    broadcast key
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1166): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1166): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1166): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1166): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1166): set send_ind_to_ndc = 0
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1166): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  911): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1166): EAPOL authentication completed successfully
I/wpa_supplicant( 1166): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
D/Tethering(  911): interfaceStatusChanged wlan0, true
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  911): [isWifi] getHotspotEnabled: false
I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/WifiStateMachine(  911): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  911): acquireWL(4431f498): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(4431f498): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  911): This record is existed, only update it...
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/WISPrService( 3830): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3830): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  911): acquireWL(439c7f60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/PMS     (  911): releaseWL(439c7f60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOn: 1452109924791
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOn: 1452109924791
D/DhcpStateMachine(  911): [StoppedState] Start DHCP
D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
D/WifiStateMachine(  911): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  911): acquireWL(44378238): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 911 1000 null
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  911):    returned true
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42211d68
D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 1
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiNative-wlan0(  911):    returned true
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42211d68, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@41eba0d0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  911):    returned null
E/WifiStateMachine(  911): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  911):    returned null
D/WifiStateMachine(  911): handlePreDhcpSetup mBluetoothConnectionActive: false
D/PMN     (  911): goingToSleep
D/WifiP2pService(  911): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428cf4b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428cf4b8 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  911): acquireWL(43d27e90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
,D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
,I/AlarmManager(  911): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20624 mDataStallAlarmIntent=null
D/PMS     (  911): releaseWL(43d27e90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:Off
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1166): get_ip_address source addr = 02000000
I/wpa_supplicant( 1166): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  911):    returned true
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  911): acquireWL(43c2b7f0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/PMS     (  911): releaseWL(43c2b7f0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/NetworkPolicy(  911): updateScreenOn: false
D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
D/ContactMessageStore( 1248): Background delete complete
,W/dalvikvm( 4584): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
D/PMS     (  911): acquireWL(438f92a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(438f92a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(43666ab8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(43666ab8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOff
,W/dalvikvm( 4584): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4584): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4584): Verify
,D/WifiService(  911): New client listening to asynchronous messages
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4584): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4584): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4584): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  911): killProcessQuiet, pid=4295
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 4295:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4295
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  911): Client connection lost with reason: 4
,D/AutoSetting( 1318): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  911): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4621 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
,D/AutoSetting( 1318): Util - no network available!
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
D/AutoSetting( 1318): service - onCreate()
D/AutoSetting( 1318): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  911): request 427313f8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1318): service - mHandler: cancel location update
,D/AutoSetting( 1318): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4584): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4584): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4621): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4621): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4621): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4621): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4584): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  911): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4637 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4621/10079)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4621/10079)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4621/10079)
,I/ActivityManager(  911): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4651 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=4064
,I/ActivityManager(  911): Killing 4064:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
E/dalvikvm( 4584): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4584): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4584): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4584): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4584): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4584): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/dalvikvm-heap( 4584): Grow heap (frag case) to 9.957MB for 84664-byte allocation
E/dalvikvm( 4584): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4584): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4584): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4584): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4584): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4584): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4584): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4584): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4651): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4651): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4651): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4651): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4584): Grow heap (frag case) to 9.971MB for 28144-byte allocation
E/dalvikvm( 4584): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4584): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4584): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4584): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4651): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4584): Grow heap (frag case) to 10.012MB for 39954-byte allocation
,I/dalvikvm-heap( 4584): Grow heap (frag case) to 10.087MB for 79892-byte allocation
I/ActivityManager(  911): Recipient 4064
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4651/10151)
,V/WebViewChromiumFactoryProvider( 4651): Binding Chromium to main looper Looper (main, tid 1) {41da7130}
,I/LibraryLoader( 4651): Expected native library version number "",actual native library version number ""
I/chromium( 4651): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4651): Initializing chromium process, renderers=0
,D/PMS     (  911): acquireWL(442ba088): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4651): BLUETOOTH permission is missing!
D/PMS     (  911): acquireWL(443ece38): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): releaseWL(442ba088): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4651): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4651): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4651): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4651): Local Branch: 
I/Adreno-EGL( 4651): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4651): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4651):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4651): Starting up...
D/wpa_supplicant( 1166): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1166): EAPOL: disable timer tick
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4651/10151)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4651/10151)
,I/dalvikvm-heap( 4584): Grow heap (frag case) to 10.275MB for 75760-byte allocation
,D/Process (  911): killProcessQuiet, pid=4328
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
I/ActivityManager(  911): Killing 4328:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4328
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c4eec0 u0 ReceiverList{43c4eda0 4584 com.facebook.katana/10027/u0 remote:429dacd0}}
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c4eec0 u0 ReceiverList{43c4eda0 4584 com.facebook.katana/10027/u0 remote:429dacd0}}
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42bb3a40 u0 ReceiverList{42bb39e0 4584 com.facebook.katana/10027/u0 remote:43409df0}}
,I/iu.Environment( 2179): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2179): num queued entries: 0
,I/iu.UploadsManager( 2179): num updated entries: 0
,I/iu.SyncManager( 2179): NEXT; no task
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4689 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  911): acquireWL(43e92420): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43e92420): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4689): isEpsOn(), nState = 0
D/PMS     (  911): acquireWL(43c406f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4689 1000 null
,D/PMS     (  911): releaseWL(43c406f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4584): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/SmartSyncUtils( 4689): getMobilePolicyEnabled, result = true
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4584): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4584): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/Process (  911): killProcessQuiet, pid=4360
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4360:com.google.android.apps.docs/u0a100 (adj 15): empty #17
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1318): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3830): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3830): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3830): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3830): Cust_ConnectToPC   : spcsc>false
D/        ( 3830): Cust_ConnectToPC   : IPT>true
D/        ( 3830): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3830): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3830): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3830): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3830): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/ActivityManager(  911): Recipient 4360
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PSReceiver( 3830): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3830): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3830): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3830):  defaultType:0
,W/ContextImpl( 4689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4689): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4689): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4689): isEpsOn(), nState = 0
D/WifiService(  911): New client listening to asynchronous messages
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41eba0d0
,W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41eba0d0, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41eba0d0, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41eba0d0
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42598740 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42598740 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-, SUCCESS
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
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(44378238): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  911): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): gateway: /192.168.1.1
,D/WifiNative-wlan0(  911): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1166): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  911):    returned true
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  911): VerifyingLinkState enter
D/WifiStateMachine(  911): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  911): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  911): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  911): WAN detection
V/NetworkPolicy(  911): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  911): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  911): default: teardown()
,D/WISPrService( 3830): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/MDST    (  911): default: setTeardownRequested(true)
D/MDST    (  911): default: setEnableApn apnType =default , enable=false
D/MDST    (  911): default: setTeardownRequested(true)
D/ConnectivityService(  911): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  911): Unexpected mtu value: android.net.wifi.WifiStateTracker@4272d9e0
D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  911): syncGetConfiguredNetworks
,D/ConnectivityService(  911): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
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
D/ConnectivityService(  911): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  911): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  911): handleConnectivityChange: resetting
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  911): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  911): acquireWL(43a4e090): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WirelessDisplayService(  911): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  911):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4621/10079)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1166): Change stage from stage0 to stage3
,D/PMS     (  911): acquireWL(4285e238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1452109876864 min interval config: 0 actual interval: 49709
D/PMS     (  911): acquireWL(426d58e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(4285e238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2179): Checking schedule, now: 1452109926581 next: 1452109906646
,I/CheckinService( 2179): active receiver: enabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2179, uid=10029, userID:0
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2179): Preparing to send checkin request
,I/EventLogService( 2179): Accumulating logs since 1452109872716
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  911): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  911): releaseWL(43a4e090): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  911): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4743 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4743): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4743): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4743): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4743): install
,I/MultiDex( 4743): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4743): loading existing secondary dex files
,I/MultiDex( 4743): load found 3 secondary dex files
,I/MultiDex( 4743): install done
,W/dalvikvm( 4743): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4743): VFY: unable to resolve instance field 36
,W/dalvikvm( 4743): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4743): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4743): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4743): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4743): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4743): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4743): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4743): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4743): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4743): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/WearableService( 1228): callingUid 10029, callindPid: 1228
,E/MDM     ( 1228): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2179): Restart initialization of location
,W/GCoreFlp( 1228): No location to return for getLastLocation()
,W/FusedLocationProvider( 1228): location=null
D/PMS     (  911): acquireWL(42863ac0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42863ac0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
D/AuthorizationBluetoothService( 1363): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1363): Proximity feature is not enabled.
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4743): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2414883297
,I/WVCdm   (  371): CdmEngine::CloseSession
,W/dalvikvm( 4510): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4510): threadid=1: thread exiting with uncaught exception (group=0x41972e30)
D/PMS     (  911): releaseWL(421b38d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  911): NetTransition Wakelock for ConnectedState released by timeout
,E/AndroidRuntime( 4510): FATAL EXCEPTION: main
E/AndroidRuntime( 4510): Process: com.test.thalitest, PID: 4510
E/AndroidRuntime( 4510): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4510): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4510): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4510): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4510): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4510): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4510): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4510): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4510): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4510): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4510): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4510): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4510): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4510): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4510): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4510): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4510): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4510): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4510): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  911): App crashed! Process: com.test.thalitest
W/ActivityManager(  911):   Force finishing activity com.test.thalitest/.MainActivity
,I/Adreno-EGL( 4743): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4743): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4743): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4743): Local Branch: 
I/Adreno-EGL( 4743): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4743): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4743):                  aa63bbd948f41d15fc72f585e
,D/Process (  911): killProcessQuiet, pid=4376
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  911): Killing 4376:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  911): bSetPropertyMultiRAB:false
,D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  911): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  911): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  911): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  911): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  911): Found interface wlan0
,D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/Process ( 4510): killProcess, pid=4510
,D/Process ( 4510): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1278): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
,D/CaptivePortalTracker(  911): NoActiveNetworkState
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1278/10076)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4621/10079)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
I/NetworkMonitor( 4564): type=WIFI subType= reason=null isConnected=true
,D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.musicenhancer (3922/10053)
D/PMS     (  911): acquireWL(426b86a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (4564/10154)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
I/ActivityManager(  911): Recipient 4376
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  911): acquireWL(43f40688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  911): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
D/PMS     (  911): releaseWL(43f40688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  911): releaseWL(426b86a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1976/10021)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/Adreno-EGL( 4743): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4743): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4743): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4743): Local Branch: 
I/Adreno-EGL( 4743): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4743): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4743):                  aa63bbd948f41d15fc72f585e
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,E/ExternalAccountType( 1349): Unsupported attribute readOnly
,D/AutoSetting( 1318): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4621): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4621): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1318): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
,D/AutoSetting( 1318): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1318): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (4743/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4651/10151)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
,E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1213): !!! FAILED BINDER TRANSACTION !!!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/InputMethodManagerService(  911): Got RemoteException sending setActive(false) notification to pid 4510 uid 10389
I/ActivityManager(  911): Recipient 4510
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.test.thalitest (pid 4510) has died.
D/PMS     (  911): acquireWL(441e7f80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
I/WindowState(  911): WIN DEATH: Window{427b9c80 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  911): Client connection lost with reason: 4
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1452109876864 min interval config: 0 actual interval: 50838
D/PMS     (  911): releaseWL(441e7f80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2179): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2179): num queued entries: 0
,I/iu.UploadsManager( 2179): num updated entries: 0
,I/iu.SyncManager( 2179): NEXT; no task
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1363): [NET] getaddrinfo-,err=8
D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1363): [NET] getaddrinfo-, 1
,D/libc    ( 1363): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a63b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  911): acquireWL(43fc9288): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 227
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1363): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1363): [NET] getaddrinfo-,err=8
,D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1363): [NET] getaddrinfo-,err=8
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/PMS     (  911): acquireWL(43f24238): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/PMS     (  911): releaseWL(43fc9288): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
,D/PMS     (  911): releaseWL(43f24238): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44337528): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
,D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/PMS     (  911): releaseWL(44337528): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,W/Settings( 4743): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4743): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4743): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4743): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4743): Local Branch: 
I/Adreno-EGL( 4743): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4743): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4743):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2801346337
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2179): [NET] getaddrinfo-,err=8
D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2179): [NET] getaddrinfo-, 1
D/libc    ( 2179): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b311 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 293
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2179): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=12 [16][2][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I/CheckinTask( 2179): Sending checkin request (12262 bytes)
,D/PMS     (  911): releaseWL(443ece38): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,W/fb4a(:<default>):UserScope( 4584): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4584): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=10 [10][1][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(4322bfb0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4564 10154 null
,W/ContextImpl( 4564): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4564, uid=10154, userID:0
,I/MusicLeanback( 4564): Conditions not met for autocaching.
,I/MusicLeanback( 4564): Stop autocaching.
D/PMS     (  911): releaseWL(4322bfb0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4564): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,E/fb4a(:<default>):LocalFbBroadcastManager( 4584): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,I/CheckinTask( 2179): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027),
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4584/10027)
,I/CheckinService( 2179): Checking schedule, now: 1452109929136 next: 1452632866127
,I/CheckinService( 2179): active receiver: disabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,I/CheckinService( 2179): Checking schedule, now: 1452109929158 next: 1452632866127
,I/CheckinService( 2179): active receiver: disabled
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,D/CheckinService( 2179): Recording last checkin time for package unspecified as 1452109929164
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/PMS     (  911): releaseWL(426d58e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/GCM     ( 1363): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d345 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 17
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  911): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4651): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  911): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4400
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4400:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 4400
,D/AutoSetting( 1318): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1318): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1318): service - requestNLP() NetworkLocationProvider not enabled
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/ActivityManager(  911): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4802 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1278): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,W/SystemReader( 1261): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1278): Deferring update until onResume
,D/Launcher( 1278): waitUntilResume // bindAppsUpdated
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO",
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
,E/ExternalAccountType( 1349): Unsupported attribute readOnly
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/dalvikvm( 4802): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4802): VFY: unable to resolve instance field 36
,W/dalvikvm( 4802): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Babel   ( 4802): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4802): MmsConfig.loadMmsSettings
,V/JNIHelp ( 4802): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  911): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4825 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,D/MessageFrequencyProvider( 4825): onCreate
,V/GetPrviateResource( 4825): GetPrviateResource
,V/GetPrviateResource( 4825): GetPrviateResource
,D/MmsCustomizationProvider( 4825): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4825): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4802, uid=10111, userID:0
,I/Babel   ( 4802): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4802): MmsConfig.loadFromDatabase
,W/Settings( 4802): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 4802): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4802): MmsConfig.loadFromResources
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4802, uid=10111, userID:0
,E/Babel   ( 4802): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4802): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4802, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4802, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4802, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4802, uid=10111, userID:0
,D/PMS     (  911): acquireWL(434077a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4802 10111 null
I/ProviderInstaller( 4802): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 4825): sense_version=6.0
,D/BTAccessoryUtil( 4825): createReceiver
,D/BTAccessoryUtil( 4825): registerReceiver return intent = null
D/MessageCustFlag( 4825): sku_id=99
,W/SystemReader( 4825): Cannot find message_ambs_application_id, use default value instead
,D/Process (  911): killProcessQuiet, pid=3922
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  911): Killing 3922:com.htc.musicenhancer/u0a53 (adj 15): empty #17
I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
D/Messaging( 4825): supportCMAS(SIE)/init? false/true
I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
D/MmsConfig( 4825): networkCode: 
D/MessageCustFlag( 4825): sku_id=99
D/MmsConfig( 4825): SIE smsPri: null
D/MmsConfig( 4825): networkCode: 
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/HtcTelephonyCapability( 4825): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4825): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4825): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4825): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  911): Resuming delayed broadcast
,I/IcingCorporaProvider( 2857): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3922
,D/PMS     (  911): acquireWL(42913138): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42913138): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(435dd210): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(434077a0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  911): killProcessQuiet, pid=4347
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4347:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 4347
,D/PMS     (  911): releaseWL(435dd210): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  911): acquireWL(43f1f8f0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  911): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  911): releaseWL(43f1f8f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(4293dfa0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43549e40): PARTIAL_WAKE_LOCK  AsyncService 0x1 3651 10160 null
,D/PMS     (  911): releaseWL(43549e40): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  911): releaseWL(4293dfa0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  911): acquireWL(443fce20): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(443fce20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,W/PackageManager(  911): Unable to load service info ResolveInfo{437f3320 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/ActivityManager(  911): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  911): acquireWL(4449b7c8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4449b7c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2179): Null package name or gms related package.  Ignoreing.
D/PMS     (  911): acquireWL(4448f3d8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2179): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2857): UpdateCorporaTask done [took 685 ms] updated apps [took 685 ms] 
I/ActivityManager(  911): Resuming delayed broadcast
,D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  911): start
,I/GCoreNlp( 1228): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  911): acquireWL(4229ea70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4229ea70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41e35de8 +
I/Prism.WidgetManager( 1278): onLoadItems() +
,D/PMS     (  911): acquireWL(4203a960): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4203a960): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  911): applying state to connected service
,D/LocationProviderProxy(  911): applying state to connected service
D/PMS     (  911): acquireWL(42777228): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42777228): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(42719708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42719708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1278): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1278): onLoadItems() -
,I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41e35de8 -
,D/PhoneApp( 1248): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1248): -- N1 =0
,D/PhoneApp( 1248): -- N2 =0
,D/PhoneApp( 1248): -- N3 =0
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Messaging( 4825): mNeedToUpdateDate2 start
,D/MmsConfig( 4825): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4825): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4825): 
D/MmsAsyncWorkHandler( 4825): HM tk = 20001
D/ReportIndicatorCache( 4825): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4825): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41da94d8
,I/Messaging( 4825): mccmnc> 
D/DraftCache( 4825): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4825): [DraftCache/1] refresh
,D/MmsConfig( 4825): networkCode: 
,D/Messaging( 4825): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1248):  phoneType = -1
,D/MessageCustFlag( 4825): sense_version=6.0
,D/PMS     (  911): releaseWL(4448f3d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4825): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4825): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4825): createReceiver
D/Jerry   ( 4825): start to preload cursor >>>>>>>
D/TelephUtils( 1248): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
V/MmsProvider( 1248): Update uri=content://mms, match=0
V/MmsProvider( 1248): selection=st=129 AND m_type!=134
D/Messaging( 4825): Reset downloading state: 0
V/MmsSystemEventReceiver( 4825): TransactionService is going to be woken up.
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/AccFlag ( 1248): sku_id=99
V/TransactionService( 4825): 1-Creating TransactionService
D/DraftCache( 4825): [DraftCache/478] rebuildCache
V/TransactionService( 4825): onStartCommand: 1
D/MmsSystemEventReceiver( 4825): unRegisterForConnectionStateChanges
V/TransactionService( 4825): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4825): Loading previous transactions.
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1248):  phoneType = -1
D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 4825): mNeedToUpdateDate2: false
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1248):  phoneType = -1
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1248): device_type: 1
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1248):  phoneType = -1
D/MmsSmsV2Provider( 1248): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TransactionService( 4825): Force set service start id to 1
V/TransactionService( 4825): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4825): unRegisterForConnectionStateChanges
D/TransactionService( 4825): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4825): Destroying TransactionService
D/Messaging( 4825): ViewCache CreatePreload
D/Messaging( 4825): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 4825): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/Messaging( 4825): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/Jerry   ( 1248): URI_DRAFT
D/Cust_MMSMS( 4825): _has_set_default_values_2=true
D/DraftCache( 4825): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4825): [DraftCache/478] rebuildCache time: 2
D/MmsAsyncWorkHandler( 4825): 
D/MmsAsyncWorkHandler( 4825): HM tk = 20002
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/AccFlag ( 1248): sku_id=99
D/MsgPreferenceUtils( 4825): def_index: 0
D/MsgPreferenceUtils( 4825): globalIndex = 1
D/MsgPreferenceUtils( 4825): phone state: true
D/MsgPreferenceUtils( 4825): sd state: false
D/MsgPreferenceUtils( 4825): vIndex = 0
D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1248): sku_id=99
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{42cb5618 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  911): acquireWL(427b9520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{439e8a30: PendingIntentRecord{428f4328 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122630, Int=0
,D/PMS     (  911): releaseWL(427b9520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(426d3fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0,
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [11][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  911): acquireWL(4270fe08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4802): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  911): releaseWL(4270fe08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(426d3fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4290d638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/PMS     (  911): releaseWL(4290d638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44408000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  911): acquireWL(42e79168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4432e1d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1228): Vacuum at: now=1452109942504 tag=VacuumService
D/PMS     (  911): releaseWL(44408000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42e79168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42eb0838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(42eb0838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(42804118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
D/PMS     (  911): releaseWL(42804118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): acquireWL(437aa788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/PMS     (  911): releaseWL(4432e1d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(43d23e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(437aa788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42661c80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43d23e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926,
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/PMS     (  911): releaseWL(42661c80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44397af8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/PMS     (  911): releaseWL(44397af8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44423220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(44423220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(441e7e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/BatteryService(  911): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(441e7e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(429569f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(429569f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(42958968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{431a6a80: PendingIntentRecord{428824b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135270, Int=0
,D/PMS     (  911): releaseWL(42958968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/PMS     (  911): acquireWL(428f3518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/PMS     (  911): acquireWL(43d21ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(428f3518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1166): Change stage from stage3 to stage0
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1228): Scheduling Phenotype for one-off execution 6077 seconds from now (1452109955428)
,D/GetConfigurationSnapshotOperation( 1228): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1228): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1228): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1228): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1228): [NET] getaddrinfo-, 1
,D/libc    ( 1228): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cd96 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 29
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1228): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(43d21ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(429898e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/PMS     (  911): releaseWL(429898e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(434a4950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/PMS     (  911): releaseWL(434a4950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1318): service - handleMessage() stop self
,D/AutoSetting( 1318): service - mHandler: update timezone
,D/AutoSetting( 1318): service - onDestroy() END
,D/AutoSetting( 1318): service - handleMessage() quit looper
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41dbf778 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 10 2 11
,D/PMS     (  911): acquireWL(43f1d8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42802528: PendingIntentRecord{4264d370 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142222, Int=0
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(433dbd68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(43f1d8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ff58 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 57
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo_proxy-, success
I/global  (  911): call createSocket() return a new socket.
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  911): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  911): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  911): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  911):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  911): killProcessQuiet, pid=4432
,I/ActivityManager(  911): Killing 4432:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 4432
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): releaseWL(433dbd68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{43f29810 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  911): acquireWL(44012078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=160349, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44012078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClearcutLoggerApiImpl( 1363): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4447
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4447:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4447
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(43a52530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10027}
,V/AlarmManager(  911): sending alarm PendingIntent{42622378: PendingIntentRecord{43a539e0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173527, Int=0
,D/PMS     (  911): releaseWL(43a52530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(43c25378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(43c25378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(434c2fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(434c2fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(43c74548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=220349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43c74548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(4432e540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4432e540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(43a3b138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=280350, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43a3b138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(43f56820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43f56820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42f2bcc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=340350, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42f2bcc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  911): killProcessQuiet, pid=4039
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4039:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4039
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(43af59b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43af59b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(4292b328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=400349, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4292b328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(438201b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(438201b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(428c8300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=460350, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(428c8300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(442b9b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(442b9b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(429c08d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=520349, Int=0
,D/PMS     (  911): releaseWL(429c08d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4341ae08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4341ae08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4317e170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=580350, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4317e170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42ed0a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42ed0a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(4382c648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4382c648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1248): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1248): sku_id=99
D/ContactMessageStore( 1248): start background delete task...
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/PMS     (  911): acquireWL(436eb328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=640349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(436eb328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(428faa90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(428faa90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(428efcf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(428efcf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42968d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=700349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42968d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43a2b190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43a2b190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/ContextImpl( 4689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3830): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3830): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3830): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3830): Cust_ConnectToPC   : spcsc>false
,D/        ( 3830): Cust_ConnectToPC   : IPT>true
,D/        ( 3830): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3830): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3830): Index of the first 1 = 3
W/Settings( 3830): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3830): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3830): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3830): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 3830): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43a48e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  911): releaseWL(43a48e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(4450e3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=760349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4450e3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43a8ca80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43a8ca80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43ef6928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(43ef6928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43843200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=820350, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1278): Grow heap (frag case) to 12.616MB for 50416-byte allocation
,D/PMS     (  911): releaseWL(43843200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42eba070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42eba070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(435d8550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(435d8550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42939d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=880349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42939d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(44315c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44315c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4354bfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  911): releaseWL(4354bfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43960be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=940349, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43960be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(434e61f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
,D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(434e61f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43a2c298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(43a2c298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43f22538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1000350, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43f22538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4322cd10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{420aa498: PendingIntentRecord{42738198 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782849, Int=0,
,I/ActivityManager(  911): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4927 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  911): sending alarm PendingIntent{4356c600: PendingIntentRecord{435836b0 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,I/ActivityManager(  911): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4939 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  911): sending alarm PendingIntent{423bd9b0: PendingIntentRecord{4239b160 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452110032239, Int=10800000
,V/AlarmManager(  911): sending alarm PendingIntent{427f3fe0: PendingIntentRecord{427d8220 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452110752634, Int=900000
,V/AlarmManager(  911): sending alarm PendingIntent{4395fc98: PendingIntentRecord{4450a1d0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452110826198, Int=0
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,W/ContextImpl( 4689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4689): call getInstance()
,D/SmartSyncUtils( 4689): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4689): MY_DEBUG = false
D/ConnectivityService(  911): Done.
D/ConnectivityService(  911): Setting timer for 720seconds
D/PMS     (  911): acquireWL(431b72a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4689 1000 null
D/PMS     (  911): releaseWL(4322cd10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4689): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4689): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4689): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4689): SettingOnTime = 1452146400000, randomSettingOnTime = 1452143669000
,D/SmartSyncScreenOnOffTimeReceiver( 4689): SettingOffTime = 1452132000000, randomSettingOffTime = 1452133595000
,D/SmartSyncScreenOnOffTimeReceiver( 4689): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4689): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4689): bNightModeTurnOffOnce = false
,I/ImageRamCache( 4927): create image Cache, size: 31457280.
I/ImageRamCache( 4927): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4927): create image Cache, size: 12582912.
,I/FeedSettings( 4927): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4927): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4927): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4927): changeLocale(): en_GB
W/BatSI   (  911): Couldn't get kernel wake lock stats
D/PMS     (  911): releaseWL(431b72a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.aurora (4939/10049)
,I/Prism.AllAppsOptionsMa_( 4927): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4927): loadGridSize() with Alternative
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/libc    ( 4927): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4927): [NET] getaddrinfo-,err=8
D/libc    ( 4927): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4927): [NET] getaddrinfo-, 1
,D/libc    ( 4927): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =54ab +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/Process (  911): killProcessQuiet, pid=4480
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4480:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4480
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(43261608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{43c1c1d8: PendingIntentRecord{4295ddf8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1008396, Int=0
,D/PMS     (  911): acquireWL(428209c8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(428209c8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43261608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4201d6a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1363/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/PMS     (  911): releaseWL(4201d6a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  364): [NET]Querying server xid =54ab (# 1) address = 192.168.1.1 (try=2,nscount=1)
,D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=8 [125][10][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11
D/libc    (  364): [NET]res_nsend:resplen=206
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4927): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.launcher (4927/10076)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.launcher (4927/10076)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024342
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024720
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024922
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024926
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024929
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026257
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026268
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029278
,D/Process (  911): killProcessQuiet, pid=4621
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4621:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4621
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(426d93a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(426d93a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(428c0130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(428c0130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43a5b8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1060350, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43a5b8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4292a068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4292a068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(428b8c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/PMS     (  911): releaseWL(428b8c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43286570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1120349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43286570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43ee8090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
,D/PMS     (  911): releaseWL(43ee8090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(44378108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44378108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(438cfce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1180349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(438cfce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43468f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(43468f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(4288a618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/PMS     (  911): releaseWL(4288a618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43708a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1240349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43708a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42915208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(42915208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(428b6d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/PMS     (  911): releaseWL(428b6d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(44405c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1300349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44405c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(439c7d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(439c7d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(429e91d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(429e91d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(444a0ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1360349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(444a0ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4364cee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4364cee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43e79f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43e79f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(438ffa78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1420349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1278): Grow heap (frag case) to 12.615MB for 50416-byte allocation
,D/PMS     (  911): releaseWL(438ffa78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4294c910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4294c910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43fc5e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1480349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43fc5e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42808e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42808e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43213188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
,I/BatteryService(  911): n_update end
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  911): releaseWL(43213188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(428cd9e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1540349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(428cd9e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43a8bf98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(43a8bf98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43f22700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1600349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43f22700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42eb03d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/PMS     (  911): releaseWL(42eb03d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(4431c138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4431c138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(44316470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1660349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44316470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(444ba760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(444ba760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43f84d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43f84d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43986340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1720349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43986340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42e83f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/PMS     (  911): releaseWL(42e83f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(44347a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(44347a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(4290e400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1780349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4290e400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/PMS     (  911): acquireWL(442fb730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(442fb730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(436472a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(436472a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/ProcessStatsService(  911): Prepared write state in 37ms
I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43d1fcb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1840350, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43d1fcb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(438376e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(438376e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(433b7328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(433b7328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(431d7688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41eb2938: PendingIntentRecord{41e4eca0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1900349, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(431d7688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4993): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4993): ====startRecUseTime====
D/htc.customization.log.level( 4993):  is 
W/CustomizationLogLevel( 4993): Level value is invalid, use default level 2
D/CustomizationManager( 4993):  Read ACC file spent 0.097 (s)
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4993): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4993): Parsing tag category name = system
I/CustomizationCIDLoader( 4993): Parsing tag category name = application
I/CustomizationCIDLoader( 4993): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4993): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4993): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4993): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4993): Parsing tag category name = Settings
D/CustomizationManager( 4993):  Read CID file spent 0.152 (s)
D/CustomizationManager( 4993):  All configurations done spent 0.153 (s)
W/HtcNativeFlag( 4993): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4993): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4993): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4993): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4993, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  911): killProcessQuiet, pid=4564
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  911): killProcessQuiet, pid=4651
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  911): Killing 4564:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  911): Killing 4651:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/Process (  911): killProcessQuiet, pid=4637
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  911): Killing 4637:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4564
D/MediaRouterService(  911): Client com.google.android.music (pid 4564): Died!
I/ActivityManager(  911): Recipient 4637
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  911): Copying FileAsset 0x6a323f98 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  911): Skipping PackageSetting{4245f228 com.example.hello/10397} due to missing metadata
I/ActivityManager(  911): Recipient 4651
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1228): Ignoring removeGeofence because network location is disabled.
D/PMS     (  911): acquireWL(43ed5cd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/Prism.ItemManager( 4927): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4927): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/Launcher( 1278): Deferring update until onResume
D/PMS     (  911): releaseWL(43ed5cd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/VoicemailCleanupService( 1291): Cleaning up data for package: com.test.thalitest
D/Launcher( 1278): waitUntilResume // bindAppsRemoved
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1278): action: android.intent.action.PACKAGE_REMOVED
E/ExternalAccountType( 1349): Unsupported attribute readOnly
W/SystemReader( 1261): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/IcingCorporaProvider( 2857): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5008 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
W/Parcel  ( 1261): Reading a NULL string not supported here.
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  911): acquireWL(427772a8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2857): UpdateCorporaTask done [took 265 ms] updated apps [took 265 ms] 
E/SQLiteDatabase( 5008): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5008): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5008): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5008): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5008): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5008): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5008): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5008): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5008): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5008): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5008): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5008): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5008): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5008): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5008): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5008): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5008): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5008): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5008): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5008): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5008): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5008): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5008): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5008): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5008): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5008): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5008): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5008): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5008): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5008): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5008): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5008): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5008): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5008): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5008): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5008): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5008): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5008): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5008): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5008): threadid=11: thread exiting with uncaught exception (group=0x41972e30)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5008): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5008): Process: com.google.android.apps.docs, PID: 5008
E/AndroidRuntime( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5008): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5008): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5008): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5008): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5008): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 5008): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5008): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5008): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5008): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5008): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5008): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5008): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5008): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5008): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5008): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5008): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5008): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5008): Opened ClientFlag.db in read-only mode
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5027 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 5008): killProcess, pid=5008
D/Process ( 5008): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  911): Recipient 5008
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 5008) has died.
W/ContextImpl( 5027): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5041 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5027): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5027): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5027): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5027): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5027): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5027): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5027): threadid=10: thread exiting with uncaught exception (group=0x41972e30)
E/AndroidRuntime( 5027): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5027): Process: com.android.keychain, PID: 5027
E/AndroidRuntime( 5027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5027): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5027): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5027): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5027): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5027): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  911): App crashed! Process: com.android.keychain
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 5041): getInstance(Context context)
D/AppTag  ( 5041): getInstance(Context context)
D/AppTag  ( 5041): onCreate()
D/Process ( 5027): killProcess, pid=5027
D/Process ( 5027): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452111731286.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  911): Recipient 5027
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.android.keychain (pid 5027) has died.
D/PMS     (  911): acquireWL(434ea3d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3651 10160 null
W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  911): Resuming delayed broadcast
W/dalvikvm( 4152): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PMS     (  911): releaseWL(434ea3d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2179): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2179): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2179): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2179): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2179): Module APK com.google.android.play.games already loaded
I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2179): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2179): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2179): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2179): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65364008
E/SQLiteDBG( 2179): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e1bb008
W/dalvikvm( 2179): threadid=42: thread exiting with uncaught exception (group=0x41972e30)
E/DriveAsyncService( 2179): disk I/O error (code 3850)
E/DriveAsyncService( 2179): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2179): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2179): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2179): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2179): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2179): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2179): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2179): Process: com.google.android.gms, PID: 2179
E/AndroidRuntime( 2179): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2179): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2179): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2179): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2179): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2179): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2179): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2179): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2179): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2179): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2179): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2179): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2179): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms
E/DropBoxManagerService(  911): Can't write: system_app_crash
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
D/Process ( 2179): killProcess, pid=2179
E/SQLiteDatabase( 2179): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2179): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2179): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2179): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2179): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2179): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2179): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2179): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2179): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2179): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/Prism.ItemManager( 4927): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4927): loadItems() com.htc.launcher.pageview.WidgetManager@41e0c740 +
I/Prism.WidgetManager( 4927): onLoadItems() +
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41e35de8 +
I/Prism.WidgetManager( 1278): onLoadItems() +
I/ActivityManager(  911): Recipient 2179
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.gms (pid 2179) has died.
D/PMS     (  911): handleWLDeath(427772a8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  911): Client connection lost with reason: 4
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
I/ActivityManager(  911): Resuming delayed broadcast
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20997ms
E/SQLiteLog( 1363): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1363): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5ca50878
W/dalvikvm( 1363): threadid=1: thread exiting with uncaught exception (group=0x41972e30)
E/ActivityManager(  911): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1363): FATAL EXCEPTION: main
E/AndroidRuntime( 1363): Process: com.google.process.gapps, PID: 1363
E/AndroidRuntime( 1363): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1363): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1363): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1363): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1363): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1363): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1363): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1363): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1363): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1363): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1363): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1363): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1363): 	... 10 more
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1363): killProcess, pid=1363
D/Process ( 1363): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/PackageManager(  911): Unable to load service info ResolveInfo{42e72be8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  911): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5072 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  911): Recipient 1363
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  911): Client connection lost with reason: 4
I/ActivityManager(  911): Process com.google.process.gapps (pid 1363) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20903ms
I/DeviceManagement( 5072): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5072 dbg=false s=true
I/DeviceManagement( 5072): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5072): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]

```
