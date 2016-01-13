#### Test 5590220275263c8_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
--------- beginning of /dev/log/system
I/ActivityManager(  910): Waited long enough for: ServiceRecord{4357b010 u0 com.htc.htclocationservice/.AutoSettingService}
E/cutils-trace( 4318): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4318): ====startRecUseTime====
D/htc.customization.log.level( 4318):  is 
W/CustomizationLogLevel( 4318): Level value is invalid, use default level 2
D/CustomizationManager( 4318):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4318): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4318): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4318): Parsing tag category name = system
I/CustomizationCIDLoader( 4318): Parsing tag category name = application
I/CustomizationCIDLoader( 4318): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4318): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4318): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4318): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4318): Parsing tag category name = Settings
D/CustomizationManager( 4318):  Read CID file spent 0.101 (s)
D/CustomizationManager( 4318):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 4318): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4318): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4318): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4318): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4318
D/PMS     (  910): acquireHCC(425e8038): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(44142670): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x62a510a0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1132681872
I/FeedHostManager( 1280): [onPause]
I/FeedProviderManager( 1280): onPause
I/FeedHostManager( 1280): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d4f368
I/SocialFeedProvider( 1280): +onPause
I/SocialFeedProvider( 1280): -onPause
D/PMS     (  910): acquireWL(43b2bd50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4329 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
D/PMS     (  910): acquireWL(423fbfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
I/TrimMemoryManager( 1280): [trimMemory] 20
I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{41bd6de8: PendingIntentRecord{41c1c700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=99108, Int=0
W/asset   ( 4329): Copying FileAsset 0x5c88cc88 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  910): releaseWL(423fbfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/ClockThread( 1123): now=1452695580037 next=59963
V/WebViewChromiumFactoryProvider( 4329): Binding Chromium to main looper Looper (main, tid 1) {41b1a4a0}
I/LibraryLoader( 4329): Expected native library version number "",actual native library version number ""
I/chromium( 4329): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4329): Initializing chromium process, renderers=0
W/System.err(  910): java.lang.Throwable: stack dump
D/PMS     (  910): acquireWL(42a1a618): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  910): acquireWL(43504e90): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  910): releaseWL(43504e90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@435ae7d0:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4329): 1102249688: getState(). Returning 12
I/Adreno-EGL( 4329): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4329): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4329): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4329): Local Branch: 
I/Adreno-EGL( 4329): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4329): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4329):                  aa63bbd948f41d15fc72f585e
W/chromium( 4329): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4329): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4329): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4329): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4329): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4329): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4329): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4329): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4329): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4329): CordovaWebView is running on device made by: HTC
V/LightsService(  910): setLight #0: color=#24
,W/AwContents( 4329): nativeOnDraw failed; clearing to background color.
,V/LightsService(  910): setLight #0: color=#20
,I/InputMethodManagerService(  910): Disable input method client, pid=1280
,W/ResourceType( 4329): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4329): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b61588, mServedView=org.apache.cordova.engine.SystemWebView{41b271f0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  910): Enable input method client, pid=4329
W/XT9_C   ( 1215): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1215): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1215): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1215): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4329): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +268ms
D/PMS     (  910): releaseWL(43b2bd50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,V/LightsService(  910): setLight #0: color=#1a
,V/LightsService(  910): setLight #0: color=#14
,D/JsMessageQueue( 4329): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4329): JniHelper::setJavaVM(0x415ee048), pthread_self() = 1662734960
,D/JX-Cordova( 4329): jxcore cordova android initializing
,I/SensorManager(  910): mEventCount = 1050
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 11.536MB for 63974-byte allocation
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 11.577MB for 95956-byte allocation
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 11.656MB for 143930-byte allocation
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 11.771MB for 215890-byte allocation
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 11.946MB for 323830-byte allocation
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 12.622MB for 728606-byte allocation
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 13.218MB for 1092904-byte allocation
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 14.075MB for 1639352-byte allocation
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 15.449MB for 2459024-byte allocation
,I/dalvikvm-heap( 4329): Grow heap (frag case) to 17.442MB for 3688532-byte allocation
,W/jxcore-log( 4329): Initializing JXcore engine
,W/jxcore-log( 4329): JXcore engine is ready
,W/jxcore-log( 4329): Starting JXcore engine
W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
D/PMS     (  910): releaseHCC(425e8038): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  910): releaseHCC(44142670): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4329): Platform android
W/jxcore-log( 4329): 
,W/jxcore-log( 4329): Process ARCH arm
W/jxcore-log( 4329): 
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/jxcore-log( 4329): JXcore Cordova bridge is ready!
I/jxcore-log( 4329): 
,W/jxcore-log( 4329): JXcore engine is started
,I/Choreographer( 4329): Skipped 136 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4329): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4329): Toggling radios to true
I/jxcore-log( 4329): 
,D/BluetoothAdapter( 4329): enable(): BT is already enabled..!
,D/WifiManager( 4329): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1389
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 1(ms)
D/WifiManager( 4329): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): TDLS: Tear down peers
,I/wpa_supplicant( 1166): wpa_driver_nl80211_disconnect(reason_code=3)
,D/WifiManager( 4329): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  910): setWifiEnabled: true pid=4329, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  910): New client listening to asynchronous messages
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4329): Radios toggled
I/jxcore-log( 4329): 
I/jxcore-log( 4329): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4329): 
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1166): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1166): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1166): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb84adbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
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
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set ,supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1166): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
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
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
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
D/WifiNative-wlan0(  910):    returned true
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(42f23da0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): Fast associate: Old scan results
I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  910):    returned true
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20327 mDataStallAlarmIntent=PendingIntent{426d76a0: PendingIntentRecord{4256c818 android broadcastIntent}}
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
,D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WISPrService( 3707): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3707): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiService(  910): New client listening to asynchronous messages
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 3707): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3707): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,V/NativeCrypto( 1365): Read error: ssl=0x66309f10: I/O error during system call, Connection timed out
,V/NativeCrypto( 1365): SSL shutdown failed: ssl=0x66309f10: I/O error during system call, Broken pipe
D/libc    (  366): [NET] entry_id:3   entry:0xb7f88db8  removed 
D/libc    (  366): [NET] entry_id:4   entry:0xb7f88c88  removed 
D/libc    (  366): [NET] entry_id:1   entry:0xb7f88f70  removed 
D/libc    (  366): [NET] entry_id:5   entry:0xb7f7fc20  removed 
D/libc    (  366): [NET] entry_id:2   entry:0xb7f84458  removed 
D/libc    (  366): [NET] entry_id:6   entry:0xb7f842d8  removed 
,D/libc    (  366): *************************
D/libc    (  366): *** DNS CACHE FLUSHED ***
D/libc    (  366): *************************
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(435aafc8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SCAN
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/PMS     (  910): acquireWL(4381e4d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1365/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/BatSI   (  910): WIFI scan started for: 650a0300 uid:1000
D/WifiNative-wlan0(  910):    returned false
,I//system/bin/ip(  366): RTNETLINK answers: No such process
,I/logwrapper(  366): /system/bin/ip terminated by exit(2)
D/PMS     (  910): releaseWL(435aafc8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  910): releaseWL(4381e4d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/PMS     (  910): releaseWL(42a1a618): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4382 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/CaptivePortalTracker(  910): NoActiveNetworkState
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(44136588): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(44136588): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1280/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4162/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
,I/ConnectivityHelper( 1280): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1602/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4162/10100)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,I/MusicStore( 4382): Database version: 95
,W/ContextImpl( 4382): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4382): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4382): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4382): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4382): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4382, uid=10154, userID:0
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/MediaRouterService(  910): Client com.google.android.music (pid 4382): Registered
,I/MediaRouter( 4382): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2366/10021)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4382/10154)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4402 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4382): getSelectedRoute
,I/NetworkMonitor( 4382): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4382/10154)
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4382, uid=10154, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(41dd03a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/ACRA    ( 4402): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  910): killProcessQuiet, pid=4130
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  910): releaseWL(41dd03a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  910): Killing 4130:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/ACRA    ( 4402): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4402): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  910): Recipient 4130
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4402): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4402): Preparing secondary program dexes.
V/DexLibLoader( 4402): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4402): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4402): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4402): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4402): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4402): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4402): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4402): Dex already copied
D/OdexVerifier( 4402): Odex verification is skipped.
,V/DexLibLoader( 4402): Creating class loader
,V/DexLibLoader( 4402): Finished creating class loader
V/DexLibLoader( 4402): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4402): Dex already copied
D/OdexVerifier( 4402): Odex verification is skipped.
,V/DexLibLoader( 4402): Creating class loader
,V/DexLibLoader( 4402): Finished creating class loader
V/DexLibLoader( 4402): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4402): Dex already copied
D/OdexVerifier( 4402): Odex verification is skipped.
,V/DexLibLoader( 4402): Creating class loader,
V/DexLibLoader( 4402): Finished creating class loader
V/DexLibLoader( 4402): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4402): Dex already copied
D/OdexVerifier( 4402): Odex verification is skipped.,
,V/DexLibLoader( 4402): Creating class loader
V/DexLibLoader( 4402): Finished creating class loader
,V/DexLibLoader( 4402): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4402): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4402): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4402): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4402): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4402): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4402): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4402): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4402): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-83
D/wpa_supplicant( 1166): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1166): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1166): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1166): Add randomness: count=8 entropy=3
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
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
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
I/wpa_supplicant( 1166): selected network = 1
D/wpa_supplicant( 1166): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84af4e8  current_ssid=0x0
D/wpa_supplicant( 1166): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1166): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1166): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1166): check if in concurrent case
,I/wpa_supplicant( 1166): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1777
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1166): RSN: PMKSA cache search - network_ctx=0xb84af4e8 try_opportunistic=0
D/wpa_supplicant( 1166): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1166): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1166): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1166): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1166): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1166): nl80211: Unsubscribe mgmt frames handle 0xb84ae718 (mode change)
D/wpa_supplicant( 1166): nl80211: Subscribe to mgmt frames with non-AP handle 0xb84ae718
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb84ae718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1166):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1166):   * freq=2412
D/wpa_supplicant( 1166):   * Auth Type 0
D/wpa_supplicant( 1166):   * WPA Versions 0x2
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1166): nl80211: Connect request send successfully
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1166): reply (489) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-46
I/wpa_supplicant( 1166): tsf=0000000104161085
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-54
I/wpa_supplicant( 1166): tsf=0000000104161101
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-54
I/wpa_supplicant( 1166): tsf=0000000104161096
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2452
I/wpa_supplicant( 1166): level=-83
I/wpa_supplicant( 1166): tsf=0000000104161105
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (4) end of scan result ==
,D/WifiManager( 1230): getScanResults enter 
,D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (4) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 104161085, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 104161101, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 104161096, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2452, timestamp: 104161105, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 4 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1166): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1166): nl80211: Connect event
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz,
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1166): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1166): Add randomness: count=9 entropy=4
I/wpa_supplicant( 1166): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1166): TDLS: Remove peers on association
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
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
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  910): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1166): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1166): Get randomness: len=32 entropy=5
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
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine( , 910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1166): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb84ae9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1166):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): This record is existed, only update it...
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1166): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f78b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1166):    broadcast key
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1166): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1166): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1166): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1166): wlan0: Connect to SSID: NG700
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/WifiApDatabaseHandler(  910): updateConnectedAP...
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
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1166): EAPOL authentication completed successfully
I/wpa_supplicant( 1166): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 79
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3707): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3707): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
D/DhcpStateMachine(  910): [StoppedState] Start DHCP
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(434ee450): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 1
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
,W/dalvikvm( 4402): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:2
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42440230 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42440230 target=com.android.internal.util.StateMachine$SmHandler }
,W/dalvikvm( 4402): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4402): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4402): Verify
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4402): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4402): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=1324
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 1324:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 1324
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BroadcastQueue(  910): Schedule to resend BroadcastRecord{4268d4b8 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=910 callingUid=1000} for ResolveInfo{43715b88 com.htc.sense.hsp/.weather.location.AutoSettingReceiver m=0x108000} of com.htc.sense.hsp
,W/fb4a(:<default>):UserScope( 4402): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4402): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/ActivityManager(  910): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4451 uid=10055 gids={50055, 1023, 3003, 5012}
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
W/fb4a(:<default>):UserScope( 4402): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  910): releaseWL(434ee450): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4402): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,D/WIFI_ICON( 1123): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1166): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20329 delay=15s
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  910): WAN detection
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 3707): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  910): default: setTeardownRequested(true)
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@4249f258
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
,D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    (  366): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/PMS     (  910): acquireWL(435a95e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
I/QuickSettingWifi( 1123): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/dalvikvm( 4402): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4402): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4402): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4402): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4402): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4402): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4402): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4402): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I//system/bin/ip(  366): RTNETLINK answers: No such file or directory
I/logwrapper(  366): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  366): RTNETLINK answers: No such process
,I/logwrapper(  366): /system/bin/ip terminated by exit(2)
,D/PluginProvider( 4451): PluginProvider onCreate
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 9.962MB for 84664-byte allocation
,W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
E/dalvikvm( 4402): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4402): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4402): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4402): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4402): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4402): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4402): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4402): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/PluginProvider( 4451): current plugin count: 18
D/HtcAppUPService( 4451): HtcUPDataProvider onCreate()
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(435a95e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 10.017MB for 39954-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 10.093MB for 79892-byte allocation
,D/wpa_supplicant( 1166): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1166): EAPOL: disable timer tick
,D/AutoSetting( 4451): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/Process (  910): killProcessQuiet, pid=4162
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4480 uid=10079 gids={50079, 3003, 5012}
I/ActivityManager(  910): Killing 4162:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (4451/10055)
,D/AutoSetting( 4451): service - onCreate()
I/ActivityManager(  910): Recipient 4162
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4451): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  910): request 424c06f8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/AutoSetting( 4451): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4451): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 4451): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 4451): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 4451): service - handleMessage() setting current location null
D/AutoSetting( 4451): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4451): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (4451/10055)
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 10.272MB for 75760-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{435ee5b0 u0 ReceiverList{425fc528 4402 com.facebook.katana/10027/u0 remote:42616fa0}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{435ee5b0 u0 ReceiverList{425fc528 4402 com.facebook.katana/10027/u0 remote:42616fa0}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{434f8510 u0 ReceiverList{425ef478 4402 com.facebook.katana/10027/u0 remote:425ed6c0}}
,D/MobileConnectivityChangeReceiver( 4480): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4480): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4480): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4480): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4497 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4480/10079)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
D/PMS     (  910): acquireWL(43cd9298): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4480/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4480/10079)
,I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1452695538092 min interval config: 0 actual interval: 48234
D/PMS     (  910): acquireWL(43cbebc0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43cd9298): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2174): Checking schedule, now: 1452695586336 next: 1452695568068
,I/CheckinService( 2174): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2174, uid=10029, userID:0
,I/CheckinService( 2174): Preparing to send checkin request
,I/EventLogService( 2174): Accumulating logs since 1452695534538
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4512 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/CheckinRequestBuilder( 2174): Checkin reason type: 8 attempt count: 1
D/PMS     (  910): acquireWL(439acc78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(439acc78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2174): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,W/Vold    (  349): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4512): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4402): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2174/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  349): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4402): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4533 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
,V/WebViewChromiumFactoryProvider( 4512): Binding Chromium to main looper Looper (main, tid 1) {41b13e78}
,I/LibraryLoader( 4512): Expected native library version number "",actual native library version number ""
,I/chromium( 4512): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4512): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(42744570): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,W/dalvikvm( 4533): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,E/AudioManagerAndroid( 4512): BLUETOOTH permission is missing!
,W/dalvikvm( 4533): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4533): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4533): install
,I/MultiDex( 4533): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/PMS     (  910): acquireWL(425a1218): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  910): releaseWL(42744570): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/MultiDex( 4533): loading existing secondary dex files
I/MultiDex( 4533): load found 3 secondary dex files
,I/Adreno-EGL( 4512): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4512): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4512): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4512): Local Branch: 
I/Adreno-EGL( 4512): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4512): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4512):                  aa63bbd948f41d15fc72f585e
,I/MultiDex( 4533): install done
,W/dalvikvm( 4533): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4533): VFY: unable to resolve instance field 36
,W/dalvikvm( 4533): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4533): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NSApplication( 4512): Starting up...
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3954/10160)
,D/Process (  910): killProcessQuiet, pid=4185
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3954/10160)
I/ActivityManager(  910): Killing 4185:com.htc.backup/1000 (adj 15): empty #17
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  910): Recipient 4185
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I/ProviderInstaller( 4533): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1230): callingUid 10029, callindPid: 1230
,D/LocationInitializer( 2174): Restart initialization of location
,D/AuthorizationBluetoothService( 1365): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1365): Proximity feature is not enabled.
,W/dalvikvm( 4533): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4533): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/MDM     ( 1230): [112] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 4533): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4533): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4533): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4533): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4533): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/PMS     (  910): acquireWL(43801d20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1230): No location to return for getLastLocation()
,W/FusedLocationProvider( 1230): location=null
D/PMS     (  910): releaseWL(43801d20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,I/WVCdm   (  373): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  373): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  373): CdmEngine::OpenSession
,I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4533): Install completed successfully. count=14 extracted=0
,D/WIFI_ICON( 1123): WifiActivity: 3
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WVCdm   (  373): PrepareKeyRequest: nonce=3528036236
D/PMS     (  910): releaseWL(42f23da0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1280): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 4382): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1280/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4480/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3798/10053)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4382/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1602/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/libc    (  910): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/libc    (  366): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =4950 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
I/WVCdm   (  373): CdmEngine::CloseSession
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/PMS     (  910): acquireWL(435a5960): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1602/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2366/10021)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,E/ExternalAccountType( 1349): Unsupported attribute readOnly
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 141
D/libc    (  366): [NET]res_nsend:resplen=104
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/AutoSetting( 4451): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4480): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4480): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 4451): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (4451/10055)
D/AutoSetting( 4451): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 4451): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 4451): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 4451): service - handleMessage() setting current location null
,D/AutoSetting( 4451): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4451): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (4451/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=100 [1][1][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3954/10160)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/DotMatrix( 1590): [EventService] EVENT_RESET_THEME_TIMESTAMP
I/IntentController( 1123): receive(android.intent.action.TIME_SET,4,false)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3954/10160)
,D/DotMatrix( 1590): [EventService] isTheSameDay:false,timestamp is early than today:true
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42688128): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
D/PMS     (  910): releaseWL(42688128): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): releaseWL(435a5960): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/FeedActionBar( 1280): updateLastUpdatedTime(in String) LAST UPDATED 15:31
,D/PMS     (  910): acquireWL(425b5880): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1452695538092 min interval config: 0 actual interval: 48972
D/PMS     (  910): releaseWL(425b5880): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/AlertReceiver( 4256): beginStartingService
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/PMS     (  910): acquireWL(435088b8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 4256 10013 null
,D/AlertService( 4256): start to updateAlertNotification!
,D/AlertService( 4256): No fired or scheduled alerts
,D/HtcAlertUtils( 4256): -- cancelReminderNotification --
,D/HtcAlertUtils( 4256): broadcastExistReminder!
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  910): releaseWL(435088b8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
W/AlertReceiver( 4256): stopSelfResult true
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4582 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4222c198
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4222c198, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41cbde80
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@426b66f0
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/WeatherRequest( 1123): request cur loc, but there is no sys cur
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
,I/ActivityManager(  910): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4598 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4582): can't get weather sync account
,W/Settings( 4533): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/WeatherRequest( 4582): request cur loc, but there is no sys cur
,W/Settings( 4582): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1280): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1280): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1280): com.htc.widget.weatherclock 1 5 17
,I/Adreno-EGL( 4533): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4533): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4533): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4533): Local Branch: 
I/Adreno-EGL( 4533): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4533): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4533):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4533): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4533): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4533): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4533): Local Branch: 
I/Adreno-EGL( 4533): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4533): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4533):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  373): CdmEngine::OpenSession
I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 323ms
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/NfcService( 1265): ScreenObserver: OFF
,D/NfcService( 1265): applyRouting - 0
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@440bc4d0)
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  910): Disable input method client, pid=4329
I/IntentController( 1123): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1265): applyRouting -2
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
D/PMS     (  910): acquireWL(440bc408): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1265 1027 null
D/PMN     (  910): wakingUp
D/PMS     (  910): releaseWL(440bc408): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  910): No lock screen! windowToken=null
D/PMN     (  910): onScreenOn
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  910): acquireWL(43ceb0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(43ceb0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WVCdm   (  373): PrepareKeyRequest: nonce=3742510702
,D/MtpService( 2366): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2366): [MTP][onReceive]-
,D/NfcService( 1265): applyRouting - 0
D/PMS     (  910): acquireWL(43baf4a8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4598 10071 null
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1265): applyRouting -2
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  910): acquireWL(435abbe0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1265 1027 null
D/PowerUI ( 1123): closing low battery warning: level=99
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): acquireWL(43854b80): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4598 10071 null
D/PMS     (  910): releaseWL(435abbe0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(43baf4a8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20330 delay=15s
I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
I/ClockThread( 1123): stop update clock
,I/WVCdm   (  373): CdmEngine::CloseSession
,D/TodoTaskshortcut( 4598): update TASK shortcut>
I/ActivityManager(  910): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4623 uid=10090 gids={50090, 3003, 5012, 1028}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
I/BatteryController( 1123): status:2 level:99 unsupport:false plugged:true
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:On
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
I/Adreno-EGL( 4533): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4533): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4533): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4533): Local Branch: 
I/Adreno-EGL( 4533): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4533): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4533):                  aa63bbd948f41d15fc72f585e
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,I/TodoTaskNotifyService( 4598): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  373): ParamSet string: screen_state=on
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  910): BroadcastRSSIForIMS, newrssi =-53 , oldRssi= -200
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WIFI_ICON( 1123): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/NetworkPolicy(  910): updateScreenOn: false
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/TodoTaskNotifyService( 4598): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/NotifyReceiver( 4598): stopSelfResult true
D/Process (  910): killProcessQuiet, pid=4149
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(43854b80): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  910): Killing 4149:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  910): Recipient 4149
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WorldClock.Global( 4623): isHtcDevice = true
I/WorldClock.Global( 4623): isHtcDevice = true
W/ContextImpl( 4270): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/WorldClock.AlarmUtils( 4623): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  910): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4639 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WorldClock.AlarmUtils( 4623): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4623): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1123): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): acquireWL(43bfd3c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43bfd3c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43873380): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1767): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): onScreenOn: 1452695587901
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1767): onScreenOn: 1452695587901
,D/TimeService( 4639): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452695587904
,D/Process (  910): killProcessQuiet, pid=4203
D/PMS     (  910): releaseWL(43873380): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Killing 4203:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41cbde80
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41cbde80, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@426b66f0
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/Process (  910): killProcessQuiet, pid=4233
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMN     (  910): goingToSleep
I/ActivityManager(  910): Recipient 4203
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Killing 4233:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/PMS     (  910): acquireWL(4357c678): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
D/PMS     (  910): acquireWL(439fe008): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,I/ActivityManager(  910): Recipient 4233
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,D/PMS     (  910): releaseWL(439fe008): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20330 mDataStallAlarmIntent=PendingIntent{425a68d8: PendingIntentRecord{4256c818 android broadcastIntent}}
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:Off
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1166): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/PMS     (  910): acquireWL(43390960): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
V/SRS_Proc(  373): ParamSet string: screen_state=off
,I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1452695538092 min interval config: 0 actual interval: 49858
D/NetworkPolicy(  910): updateScreenOn: false
,D/ContactMessageStore( 1251): start background delete task...
D/ContactMessageStore( 1251): size: 0 , 0
,D/ContactMessageStore( 1251): Background delete complete
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/PMS     (  910): acquireWL(43850408): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2174 10029 null
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43390960): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  910): acquireWL(43d3a338): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4533/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
D/PMS     (  910): releaseWL(43850408): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  910): releaseWL(43d3a338): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
I/CheckinRequestBuilder( 2174): Classify the device as Phone.
,D/AutoSetting( 4451): receiver - intent: android.intent.action.USER_PRESENT
,D/TetherSettings( 3707): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3707): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3707): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3707): Cust_ConnectToPC   : spcsc>false
D/        ( 3707): Cust_ConnectToPC   : IPT>true
D/        ( 3707): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3707): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3707): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3707): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3707): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3707): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 4451): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/SmartNS_PSService( 3707): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3707): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3707):  defaultType:0
,D/DotMatrix( 1590): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 3707): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  910): Resuming delayed broadcast
D/PMS     (  910): acquireWL(439e0358): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(439e0358): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(436188c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(436188c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2174): [NET] getaddrinfo-,err=8
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2174): [NET] getaddrinfo-, 1
,D/libc    ( 2174): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1767): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1767): onScreenOff
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =7c4 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/AutoSetting( 4451): service - mHandler: cancel location update
,D/AutoSetting( 4451): service -           changes count: 0
I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4662 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 170
D/libc    (  366): [NET]res_nsend:resplen=84
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2174): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2174): Sending checkin request (12245 bytes)
,W/ContextImpl( 4662): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4662): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(435ba750): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4662 1000 null
,D/PMS     (  910): releaseWL(435ba750): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4662): getMobilePolicyEnabled, result = true
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  910): acquireWL(436196b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4598 10071 null
,D/PMS     (  910): acquireWL(44085df8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4598 10071 null
,I/ActivityManager(  910): Delay finish: com.htc.task/.notification.NotifyReceiver
,E/TodoTaskNotifyService( 4598): java.lang.NullPointerException
W/System.err( 4598): java.lang.NullPointerException
W/System.err( 4598): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4598): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4598): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4598): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4598): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  910): releaseWL(436196b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  910): releaseWL(44085df8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  910): Resuming delayed broadcast
W/NotifyReceiver( 4598): stopSelfResult true
,D/Process (  910): killProcessQuiet, pid=3763
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3763:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/PMS     (  910): acquireWL(4352b3c0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4598 10071 null
I/ActivityManager(  910): Recipient 3763
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(42663e58): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4598 10071 null
,D/PMS     (  910): releaseWL(4352b3c0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4598): java.lang.NullPointerException
W/System.err( 4598): java.lang.NullPointerException
W/System.err( 4598): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4598): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4598): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4598): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4598): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4598): stopSelfResult true
,D/Process (  910): killProcessQuiet, pid=3914
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  910): releaseWL(42663e58): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  910): Killing 3914:com.google.android.gm/u0a107 (adj 15): empty #17
,W/ContextImpl( 4662): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4662): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4662): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4662): isEpsOn(), nState = 0
D/WifiService(  910): New client listening to asynchronous messages
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426b66f0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426b66f0, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426b66f0, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426b66f0
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42479d10 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42479d10 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{426915c0 u0 com.test.thalitest/.MainActivity t2}
,I/ActivityManager(  910): Recipient 3914
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,W/fb4a(:<default>):UserScope( 4402): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4402): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=20 [15][3][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,I/CheckinRequestBuilder( 2174): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2174): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2174/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4402): Called registerBroadcastReceiver twice.
,I/CheckinRequestBuilder( 2174): Classify the device as Phone.
,I/CheckinTask( 2174): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2174): Checking schedule, now: 1452695588811 next: 1453218525807
,I/CheckinService( 2174): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,I/CheckinService( 2174): Checking schedule, now: 1452695588832 next: 1453218525807
,I/CheckinService( 2174): active receiver: disabled
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
,D/CheckinService( 2174): Recording last checkin time for package unspecified as 1452695588838
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/PMS     (  910): releaseWL(43cbebc0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,D/PMS     (  910): acquireWL(4360a540): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1365): [NET] getaddrinfo-, 1
D/libc    ( 1365): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =6799 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 191
D/libc    (  366): [NET]res_nsend:resplen=79
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1365): [NET] getaddrinfo_proxy-, success
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-,err=8
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =4532 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4402/10027)
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  366): [NET]res_nsend:resplen=172
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): acquireWL(44132640): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): releaseWL(4360a540): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(44132640): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440f5c50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): acquireWL(440cab80): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4382 10154 null
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,W/ContextImpl( 4382): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 4382): Conditions not met for autocaching.
,I/MusicLeanback( 4382): Stop autocaching.
,W/ContextImpl( 4382): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
D/PMS     (  910): releaseWL(440f5c50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4382, uid=10154, userID:0
D/PMS     (  910): releaseWL(440cab80): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/PMS     (  910): releaseWL(425a1218): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=10 [10][1][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(43d27560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029}
,V/AlarmManager(  910): sending alarm PendingIntent{42465d28: PendingIntentRecord{431e36a8 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
,D/ContactMessageStore( 1251): notify MmsSms
D/AccFlag ( 1251): sense_version=6.0
,D/AccFlag ( 1251): sku_id=99
D/PMS     (  910): releaseWL(43d27560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 31
,D/AccFlag ( 1251): sku_id=99
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 72
,D/AccFlag ( 1251): sku_id=99
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 74
,D/AccFlag ( 1251): sku_id=99
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 31
,D/AccFlag ( 1251): sku_id=99
,D/PMS     (  910): acquireWL(43cf9838): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43cf9838): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43cf7d30): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.android.phone ] tid: 38
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4704 uid=10041 gids={50041}
,D/SMSBackup( 4301): Got a database change event
,D/Process (  910): killProcessQuiet, pid=3982
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  910): Killing 3982:com.android.vending/u0a74 (adj 15): empty #17
,I/Icing   ( 2174): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,I/Icing   ( 2174): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
D/PMS     (  910): releaseWL(43cf7d30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms},
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3982
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4512): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4329): Test app app.js loaded
I/jxcore-log( 4329): 
,I/Choreographer( 4329): Skipped 533 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4329): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4329): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b271f0 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4329): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  910): releaseWL(4357c678): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/Process (  910): killProcessQuiet, pid=4480
,I/ActivityManager(  910): Killing 4480:com.google.android.setupwizard/u0a79 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  910): killProcessQuiet, pid=4402
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4402:com.facebook.katana/u0a27 (adj 15): empty #18
,I/ActivityManager(  910): Recipient 4480
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4402
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,D/PMS     (  910): acquireWL(435b1fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10014}
,V/AlarmManager(  910): sending alarm PendingIntent{43d161c8: PendingIntentRecord{440e7df0 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=111182, Int=0
,D/PMS     (  910): acquireWL(42aaef18): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1544 10014 null
,D/PMS     (  910): releaseWL(435b1fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/PMS     (  910): releaseWL(42aaef18): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/AutoSetting( 1544): service - handleMessage() stop self
,D/AutoSetting( 1544): service - onDestroy() END
,D/AutoSetting( 1544): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4497
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4497:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4497
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4720 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1280): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,W/SystemReader( 1265): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/Launcher( 1280): Deferring update until onResume
,D/Launcher( 1280): waitUntilResume // bindAppsUpdated
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,E/ExternalAccountType( 1349): Unsupported attribute readOnly
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,D/PhoneApp( 1251): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4720): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4720): MmsConfig.loadMmsSettings
,W/dalvikvm( 4720): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4720): VFY: unable to resolve instance field 36
,W/dalvikvm( 4720): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4720): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4720, uid=10111, userID:0
,I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4743 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
W/Settings( 4720): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4720, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4720, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4720, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4720, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4720, uid=10111, userID:0
,D/PMS     (  910): acquireWL(4270d0b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4720 10111 null
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 4451): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4451): handle notify Blinkfeed plugin client changed
,D/MessageFrequencyProvider( 4743): onCreate
I/ActivityManager(  910): Resuming delayed broadcast
,W/PackageManager(  910): Unable to load service info ResolveInfo{42521c28 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/MmsCustomizationProvider( 4743): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4743): GetPrviateResource
,I/IcingCorporaProvider( 2816): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
V/GetPrviateResource( 4743): GetPrviateResource
,D/PMS     (  910): acquireWL(4275c7f0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/MmsCustomizationProvider( 4743): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/PMS     (  910): releaseWL(4275c7f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 4720): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4720): MmsConfig.loadFromDatabase
,D/Process (  910): killProcessQuiet, pid=4512
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  910): acquireWL(42a3df88): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4270d0b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  910): Killing 4512:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,E/Babel   ( 4720): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4720): MmsConfig.loadFromResources
,E/Babel   ( 4720): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4720): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ProviderInstaller( 4720): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 4743): sense_version=6.0
,D/BTAccessoryUtil( 4743): createReceiver
,D/BTAccessoryUtil( 4743): registerReceiver return intent = null
D/MessageCustFlag( 4743): sku_id=99
,W/SystemReader( 4743): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4743): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4743): networkCode: 
D/MessageCustFlag( 4743): sku_id=99
D/MmsConfig( 4743): SIE smsPri: null
,D/MmsConfig( 4743): networkCode: 
,D/HtcTelephonyCapability( 4743): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4743): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4743): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4743): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  910): releaseWL(42a3df88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(426bc400): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(438559d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3954 10160 null
,I/ActivityManager(  910): Recipient 4512
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3954): Grow heap (frag case) to 13.502MB for 1821008-byte allocation
D/PMS     (  910): releaseWL(438559d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  910): releaseWL(426bc400): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,I/dalvikvm-heap( 3954): Grow heap (frag case) to 15.201MB for 1821008-byte allocation
D/PMS     (  910): acquireWL(43cc7818): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43cc7818): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  910): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4770 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/PMS     (  910): acquireWL(423be0b0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(423be0b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42480aa8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42480aa8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(426bd668): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(426bd668): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/RemoteDisplayProvider(  910): start
,D/PMS     (  910): acquireWL(4383cf90): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4770, uid=10074, userID:0
,D/PMS     (  910): releaseWL(4383cf90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(435d9808): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreNlp( 1230): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  910): releaseWL(435d9808): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
,D/Finsky  ( 4770): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(441bcb50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(441bcb50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4770/10074)
D/PMS     (  910): acquireWL(4361a918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4361a918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2816): UpdateCorporaTask done [took 447 ms] updated apps [took 447 ms] 
D/PMS     (  910): acquireWL(4409a218): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4409a218): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43580f90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43580f90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4770/10074)
,D/Finsky  ( 4770): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4770): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4770): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4770, uid=10074, userID:0
,D/Ads     ( 4770): Skipping gmscore version check
,D/Finsky  ( 4770): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4770): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4770): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 4770): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2174): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(4364e630): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  910): killProcessQuiet, pid=4256
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4256:com.htc.calendar/u0a13 (adj 15): empty #17
,I/Icing   ( 2174): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  910): Recipient 4256
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1280): loadItems() com.htc.launcher.pageview.WidgetManager@41ba9db0 +
,I/Prism.WidgetManager( 1280): onLoadItems() +
,E/Prism.WidgetManager( 1280): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1280): onLoadItems() -
,I/Prism.ItemManager( 1280): loadItems() com.htc.launcher.pageview.WidgetManager@41ba9db0 -
,D/PhoneApp( 1251): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1251): -- N1 =0
,D/PhoneApp( 1251): -- N2 =0
,D/PhoneApp( 1251): -- N3 =0
,I/Icing   ( 2174): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2174): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(4364e630): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4743): mNeedToUpdateDate2 start
,D/MmsConfig( 4743): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4743): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4743): 
D/MmsAsyncWorkHandler( 4743): HM tk = 20001
,D/ReportIndicatorCache( 4743): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4743): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b27770
,I/Messaging( 4743): mccmnc> 
D/DraftCache( 4743): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4743): [DraftCache/1] refresh
,D/MmsConfig( 4743): networkCode: 
,D/Messaging( 4743): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1251):  phoneType = -1
,D/MmsSmsV2Provider( 1251): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 4743): HtcWrapEnvironment.getSupportedStorages() >1,
D/PhoneStorageUtil( 4743): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4743): createReceiver
,D/MessageCustFlag( 4743): sense_version=6.0
,D/Jerry   ( 4743): start to preload cursor >>>>>>>
D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1251): sku_id=99
D/TelephUtils( 1251): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,V/MmsProvider( 1251): Update uri=content://mms, match=0
,V/MmsProvider( 1251): selection=st=129 AND m_type!=134
,D/Messaging( 4743): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4743): TransactionService is going to be woken up.
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1251):  phoneType = -1
V/TransactionService( 4743): 1-Creating TransactionService
D/MmsSmsV2Provider( 1251): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4743): [DraftCache/475] rebuildCache
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1251):  phoneType = -1
,D/Messaging( 4743): mNeedToUpdateDate2: false
V/TransactionService( 4743): onStartCommand: 1
,D/MmsSystemEventReceiver( 4743): unRegisterForConnectionStateChanges
V/TransactionService( 4743): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4743): Loading previous transactions.
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1251):  phoneType = -1
,D/MmsSmsV2Provider( 1251): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 4743): ViewCache CreatePreload
,D/Messaging( 4743): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4743): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4743): def_index: 0
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
,D/MsgPreferenceUtils( 4743): globalIndex = 1
,D/AccFlag ( 1251): device_type: 1
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
,D/Jerry   ( 1251): URI_DRAFT
D/MsgPreferenceUtils( 4743): phone state: true
D/MsgPreferenceUtils( 4743): sd state: false
,D/MsgPreferenceUtils( 4743): vIndex = 0
,D/TransactionService( 4743): Force set service start id to 1
,V/TransactionService( 4743): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4743): unRegisterForConnectionStateChanges
D/TransactionService( 4743): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4743): Destroying TransactionService
,D/Process (  910): killProcessQuiet, pid=3798
,D/DraftCache( 4743): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4743): [DraftCache/475] rebuildCache time: 2
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/MmsAsyncWorkHandler( 4743): 
D/MmsAsyncWorkHandler( 4743): HM tk = 20002
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1251):  phoneType = -1
V/TransactionService( 4743): 4-Handling incoming message: { when=-10ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MmsSmsV2Provider( 1251): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
I/ActivityManager(  910): Killing 3798:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,D/Messaging( 4743): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
,D/AccFlag ( 1251): sku_id=99
I/ActivityManager(  910): Recipient 3798
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephUtils( 1251): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1251): sku_id=99
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{442402f0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4720): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=4582
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4582:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4582
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(440c72f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{440d9a10: PendingIntentRecord{423a4630 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=125033, Int=0
,D/PMS     (  910): releaseWL(440c72f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440b9aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [15][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43d1ab68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43d1ab68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(440b9aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43d11f90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/PMS     (  910): releaseWL(43d11f90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43d03540): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(43cf94b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43cf4c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1230): Vacuum at: now=1452695606164 tag=VacuumService
,D/PMS     (  910): releaseWL(43d03540): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43cf94b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43cd9298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43cf4c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/PMS     (  910): releaseWL(43cd9298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43cc6378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(43cc6378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43bdab60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/PMS     (  910): releaseWL(43bdab60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4383ffc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(4383ffc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42692458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0,
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(42464c88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42464c88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(425d83b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42692458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43c85720): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/PMS     (  910): releaseWL(43c85720): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1230): Scheduling Phenotype for one-off execution 13172 seconds from now (1452695606947)
,D/GetConfigurationSnapshotOperation( 1230): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1230): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1230): VFY: unable to find class referenced in signature (Landroid/net/Network;),
,W/dalvikvm( 1230): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1230): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1230): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1230): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1230): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1230): [NET] getaddrinfo-, 1
D/libc    ( 1230): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =e477 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 141
D/libc    (  366): [NET]res_nsend:resplen=87
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1230): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
,D/PMS     (  910): releaseWL(425d83b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(435a0e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/PMS     (  910): releaseWL(435a0e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43b93d90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=18 [11][2][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/PMS     (  910): releaseWL(43b93d90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440c37b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(440c37b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=99
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1123): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 4451): service - mHandler: update timezone
,D/AutoSetting( 1544): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1544): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1544): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1544): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1544): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1590): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1544): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1544): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1544): service - mHandler: update timezone
,D/AutoSetting( 1544): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1544): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1544): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1544): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1123): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{41ee68b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 4451): service - mHandler: update timezone
,D/AutoSetting( 1544): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1544): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1544): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1544): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1544): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1544): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1544): service - mHandler: update timezone
,D/DotMatrix( 1590): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1544): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1544): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1544): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1544): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1123): com.htc.htclocationservice (true,33751552),
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{41ba6990 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.htc.htclocationservice 3 8 3 11
,D/PMS     (  910): acquireWL(43cfb648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{425dd178: PendingIntentRecord{428ae098 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137192, Int=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): releaseWL(43cfb648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 4451): service - handleMessage() stop self
,D/AutoSetting( 4451): service - handleMessage() quit looper
,D/AutoSetting( 4451): service - onDestroy() END
,D/PMS     (  910): acquireWL(435b7518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(435b7518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): closing low battery warning: level=99
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1123): status:2 level:99 unsupport:false plugged:true
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/PMS     (  910): acquireWL(430455e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  910): sending alarm PendingIntent{42571618: PendingIntentRecord{424e6fb8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141916, Int=0
D/PMS     (  910): acquireWL(43431e90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(430455e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =f980 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  366): [NET]res_nsend:resplen=243
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=10
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(43431e90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1251): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1251): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{42ce9608 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(442089f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bd6de8: PendingIntentRecord{41c1c700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=159123, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(442089f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1544): service - handleMessage() stop self
,D/AutoSetting( 1544): service - onDestroy() END
,D/AutoSetting( 1544): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4623
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4623:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4623
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1251): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(42683280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42683280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(43cf2b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderNotification, total:0
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/HtcPowerSaver(  910): updateBatteryInfo
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/HeadsetPhoneState( 1634): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/PMS     (  910): releaseWL(43cf2b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/ContextImpl( 4662): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3707): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3707): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3707): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3707): Cust_ConnectToPC   : spcsc>false
D/        ( 3707): Cust_ConnectToPC   : IPT>true
D/        ( 3707): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3707): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3707): Index of the first 1 = -1
W/ContextImpl( 3707): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Settings( 3707): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3707): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3707): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3707): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3707): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 3707): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  910): acquireWL(44132b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bd6de8: PendingIntentRecord{41c1c700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=219124, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44132b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4424f758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{423be4e8: PendingIntentRecord{43728078 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=225421, Int=0
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4867 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{42539100: PendingIntentRecord{4253e110 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452695692429, Int=10800000
,D/PMS     (  910): releaseWL(4424f758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10049}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4867/10049)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024511
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024659
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024784
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024808
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024818
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024932
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026484
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029015
,D/Process (  910): killProcessQuiet, pid=4270
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4270:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4270
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(426c10d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{426da6e8: PendingIntentRecord{43cb8cd8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=226672, Int=120000
,D/PMS     (  910): releaseWL(426c10d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43cfa5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43cfa5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(435b4168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bd6de8: PendingIntentRecord{41c1c700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=279124, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(435b4168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4385cc60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4385cc60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4329): --= Surplus to requirements =--
I/jxcore-log( 4329): 
I/jxcore-log( 4329): ****TEST TOOK:  ms ****
I/jxcore-log( 4329): 
,I/jxcore-log( 4329): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4329): 
,D/CustomizationManager( 4888): ====startRecUseTime====
D/htc.customization.log.level( 4888):  is 
,W/CustomizationLogLevel( 4888): Level value is invalid, use default level 2
,D/CustomizationManager( 4888):  Read ACC file spent 0.085 (s)
D/CIDMapFileReader( 4888): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4888): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4888): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4888): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4888): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4888): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4888): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4888): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 4888): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4888): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4888): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4888): Parsing tag category name = system
,I/CustomizationCIDLoader( 4888): Parsing tag category name = application
I/CustomizationCIDLoader( 4888): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4888): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4888): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4888): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4888): Parsing tag category name = Settings
D/CustomizationManager( 4888):  Read CID file spent 0.123 (s),
,D/CustomizationManager( 4888):  All configurations done spent 0.123 (s)
,W/HtcNativeFlag( 4888): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4888): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4888): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4888): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4888, uid=2000 user=0
,I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  910): killProcessQuiet, pid=4329
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  910): Killing 4329:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  910):   Force finishing activity ActivityRecord{426915c0 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  910): Copying FileAsset 0x6d287de0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4329 uid 10389
E/JavaBinder( 1215): !!! FAILED BINDER TRANSACTION !!!
,W/PackageSettings(  910): Skipping PackageSetting{4222c530 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  910): WIN DEATH: Window{435a99b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  910): Client connection lost with reason: 4
,I/dalvikvm-heap( 3954): Grow heap (frag case) to 16.937MB for 1821008-byte allocation
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1230): Ignoring removeGeofence because network location is disabled.
,D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  910): acquireWL(429f24e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms},
D/PMS     (  910): releaseWL(429f24e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
D/VoicemailCleanupService( 1304): Cleaning up data for package: com.test.thalitest
,I/Launcher( 1280): Deferring update until onResume
,D/Launcher( 1280): waitUntilResume // bindAppsRemoved
W/SystemReader( 1265): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,W/SQLiteConnectionPool( 2174): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,I/[PluginManager]RegisterService( 4451): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 4451): handle notify Blinkfeed plugin client changed
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
,D/Prism.PackageStateRece_( 1280): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
,I/IcingCorporaProvider( 2816): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
E/cutils-trace( 4888): Error opening trace file: No such file or directory (2)
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,E/ExternalAccountType( 1349): Unsupported attribute readOnly
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4906 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1251 :
,D/PhoneApp( 1251): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  910): acquireWL(4358d7b0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2816): UpdateCorporaTask done [took 197 ms] updated apps [took 197 ms] 
,W/ProcessCpuTracker(  910): Skipping unknown process pid 4888
,W/PackageManager(  910): Unable to load service info ResolveInfo{425bb178 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4906): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4906): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4906): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4906): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4906): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4906): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4906): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4906): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4906): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4906): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4906): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4906): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4906): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4906): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4906): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4906): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4906): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4906): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4906): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4906): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4906): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4906): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4906): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4906): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4906): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4906): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4906): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4906): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4906): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4906): threadid=11: thread exiting with uncaught exception (group=0x416e6e30)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4906): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4906): Process: com.google.android.apps.docs, PID: 4906
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
E/AndroidRuntime( 4906): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4906): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4906): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4906): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4906): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  910): Can't write: system_app_crash
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
E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4906): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4906): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4906): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4906): Opened ClientFlag.db in read-only mode
D/Process ( 4906): killProcess, pid=4906
D/Process ( 4906): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4925 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  910): Recipient 4906
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4906) has died.
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4925): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4925): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4925): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4925): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4925): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4925): threadid=10: thread exiting with uncaught exception (group=0x416e6e30)
,E/ActivityManager(  910): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4925): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4925): Process: com.android.keychain, PID: 4925
E/AndroidRuntime( 4925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4925): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4925): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4925): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4925): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4938 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4925): killProcess, pid=4925
,D/Process ( 4925): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452695797598.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  910): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  910): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  910): 	... 4 more
,I/ActivityManager(  910): Recipient 4925
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Process com.android.keychain (pid 4925) has died.
,W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/AppTag  ( 4938): getInstance(Context context)
,D/AppTag  ( 4938): getInstance(Context context)
,D/AppTag  ( 4938): onCreate()
,D/PMS     (  910): acquireWL(43810458): PARTIAL_WAKE_LOCK  AsyncService 0x1 3954 10160 null
,D/PMS     (  910): releaseWL(43810458): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4770): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2174): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2174): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2174): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2174): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2174): Module APK com.google.android.play.games already loaded
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2174): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2174): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e3f0520
,W/dalvikvm( 2174): threadid=48: thread exiting with uncaught exception (group=0x416e6e30)
E/SQLiteLog( 2174): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2174): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cadf050
,I/LocationSettingsChecker( 2174): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager(  910): App crashed! Process: com.google.android.gms
,E/DriveAsyncService( 2174): disk I/O error (code 3850)
E/DriveAsyncService( 2174): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2174): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2174): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2174): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2174): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2174): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2174): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2174): Process: com.google.android.gms, PID: 2174
E/AndroidRuntime( 2174): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2174): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2174): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2174): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2174): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2174): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2174): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2174): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2174): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2174): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2174): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2174): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2174): 	at java.lang.Thread.run(Thread.java:864)
,D/Process ( 2174): killProcess, pid=2174
,D/Process ( 2174): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 2174
,I/ActivityManager(  910): Process com.google.android.gms (pid 2174) has died.
,D/WifiService(  910): Client connection lost with reason: 4
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
D/PMS     (  910): handleWLDeath(4358d7b0): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20998ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30998ms
,I/ActivityManager(  910): Resuming delayed broadcast
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30994ms
,E/SQLiteLog( 1365): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1365): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f623a8
,W/dalvikvm( 1365): threadid=1: thread exiting with uncaught exception (group=0x416e6e30)
,E/AndroidRuntime( 1365): FATAL EXCEPTION: main
E/AndroidRuntime( 1365): Process: com.google.process.gapps, PID: 1365
E/AndroidRuntime( 1365): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1365): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1365): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1365): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1365): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1365): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1365): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1365): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1365): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1365): 	... 10 more
,E/ActivityManager(  910): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
,D/Process ( 1365): killProcess, pid=1365
,D/Process ( 1365): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4966 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4966): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4966 dbg=false s=true
,I/DeviceManagement( 4966): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4966): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4966): WorkflowService: Starting workflow service
,I/DeviceManagement( 4966): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b47e40] args=[Bundle[mParcelledData.dataSize=120]]
,I/DeviceManagement( 4966): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4966): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4966): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4966): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4966): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4966): SessionStateController: Checking invariants...
I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4980 uid=10099 gids={50099, 3003, 5012}
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 1365
,I/ActivityManager(  910): Process com.google.process.gapps (pid 1365) has died.
,D/WifiService(  910): Client connection lost with reason: 4
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30830ms
,D/Documents( 4980): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4980): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4980): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4980): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4980): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4980): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4980): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4980): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4980): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4980): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4980): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4980): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4980): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4980): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4980): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4980): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4980): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4980): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4980): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4980): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4980): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4980): threadid=1: thread exiting with uncaught exception (group=0x416e6e30)
E/AndroidRuntime( 4980): FATAL EXCEPTION: main
E/AndroidRuntime( 4980): Process: com.android.documentsui, PID: 4980
E/AndroidRuntime( 4980): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4980): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4980): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4980): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4980): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4980): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4980): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4980): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4980): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4980): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4980): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4980): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4980): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4980): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4980): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4980): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4980): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4980): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4980): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4980): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4980): 	... 10 more
,I/ActivityManager(  910): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4994 uid=10023 gids={50023, 1028, 1015, 1023}
,I/ActivityManager(  910): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5006 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  910): Killing 4639:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4639
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  910): killProcessQuiet, pid=4598
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  910): Killing 4598:com.htc.task/u0a71 (adj 15): empty #17
,E/ActivityManager(  910): App crashed! Process: com.android.documentsui
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
,E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452695798192.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  910): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  910): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  910): 	... 4 more
I/ActivityManager(  910): Recipient 4598
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4639
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process ( 4980): killProcess, pid=4980
,D/Process ( 4980): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/SQLiteDatabase( 4966): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4966): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4966): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4966): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4966): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4966): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4966): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4966): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4966): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4966): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4966): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4966): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4966): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4966): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4966): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4966): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4966): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4966): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,E/SQLiteDatabase( 4966): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4966): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4966): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4966): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4966): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4966): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4966): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/DeviceManagement( 4966): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b47e40]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4966): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4966): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4966): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4966): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4966): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4966): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  910): Recipient 4980
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Process com.android.documentsui (pid 4980) has died.
D/ExternalStorage( 4994): After updating volumes, found 1 active roots
I/DeviceManagement( 4966): WorkflowService: Stopping workflow service
,W/dalvikvm( 5006): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 5006): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 5006): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5006): install
,I/MultiDex( 5006): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5006): loading existing secondary dex files
,I/MultiDex( 5006): load found 3 secondary dex files
,I/MultiDex( 5006): install done
,I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1280): loadItems() com.htc.launcher.pageview.WidgetManager@41ba9db0 +
,I/Prism.WidgetManager( 1280): onLoadItems() +

```
