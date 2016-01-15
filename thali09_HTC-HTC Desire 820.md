#### Test 561510938d3c4f5_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  911): setLight #0: color=#1b
V/LightsService(  911): setLight #0: color=#14
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{4387a950 u0 com.htc.htclocationservice/.AutoSettingService}
--------- beginning of /dev/log/main
E/cutils-trace( 4510): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4510): ====startRecUseTime====
D/htc.customization.log.level( 4510):  is 
W/CustomizationLogLevel( 4510): Level value is invalid, use default level 2
I/SensorManager(  911): mEventCount = 1200
D/CustomizationManager( 4510):  Read ACC file spent 0.067 (s)
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4510): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4510): Parsing tag category name = system
I/CustomizationCIDLoader( 4510): Parsing tag category name = application
I/CustomizationCIDLoader( 4510): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4510): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4510): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4510): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4510): Parsing tag category name = Settings
D/CustomizationManager( 4510):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4510):  All configurations done spent 0.108 (s)
W/HtcNativeFlag( 4510): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4510): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4510): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4510): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4510
D/PMS     (  911): acquireHCC(43f5bb80): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(43ee2b40): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
W/asset   (  911): Copying FileAsset 0x69dd0750 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1136033664
I/FeedHostManager( 1264): [onPause]
I/FeedProviderManager( 1264): onPause
I/FeedHostManager( 1264): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42708f30
I/SocialFeedProvider( 1264): +onPause
I/SocialFeedProvider( 1264): -onPause
D/PMS     (  911): acquireWL(42de7648): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/ActivityManager(  911): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4521 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1264): [trimMemory] 20
W/asset   ( 4521): Copying FileAsset 0x5c6eb428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4521): Binding Chromium to main looper Looper (main, tid 1) {4224c3f0}
I/LibraryLoader( 4521): Expected native library version number "",actual native library version number ""
I/chromium( 4521): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4521): Initializing chromium process, renderers=0
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@445a7370:true
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4521): 1109794344: getState(). Returning 12
D/PMS     (  911): acquireWL(43ae3bd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): acquireWL(43f902c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): releaseWL(43ae3bd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4521): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4521): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4521): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4521): Local Branch: 
I/Adreno-EGL( 4521): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4521): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4521):                  aa63bbd948f41d15fc72f585e
W/chromium( 4521): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4521): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4521): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4521): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4521): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4521): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4521): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4521): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4521): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4521): CordovaWebView is running on device made by: HTC
,W/AwContents( 4521): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  911): Disable input method client, pid=1264
W/ResourceType( 4521): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4521): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@422934d8, mServedView=org.apache.cordova.engine.SystemWebView{42259140 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1204): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1204): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1204): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1204): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  911): Enable input method client, pid=4521
W/AwContents( 4521): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  911): Displayed com.test.thalitest/.MainActivity: +283ms
D/PMS     (  911): releaseWL(42de7648): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4521): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4521): JniHelper::setJavaVM(0x41e09010), pthread_self() = 1663327312
D/JX-Cordova( 4521): jxcore cordova android initializing
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 11.954MB for 42652-byte allocation
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 12.049MB for 95956-byte allocation
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 12.128MB for 143930-byte allocation
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 12.246MB for 215890-byte allocation
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 12.417MB for 323830-byte allocation
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 12.674MB for 485740-byte allocation
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 13.676MB for 1092904-byte allocation
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 14.590MB for 1639352-byte allocation
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 15.896MB for 2459024-byte allocation
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
,D/PMS     (  911): releaseHCC(43f5bb80): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  911): releaseHCC(43ee2b40): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/dalvikvm-heap( 4521): Grow heap (frag case) to 18.029MB for 3688532-byte allocation
,W/jxcore-log( 4521): Initializing JXcore engine
,W/jxcore-log( 4521): JXcore engine is ready
,W/jxcore-log( 4521): Starting JXcore engine
,W/jxcore-log( 4521): Platform android
W/jxcore-log( 4521): 
,W/jxcore-log( 4521): Process ARCH arm
W/jxcore-log( 4521): 
,D/PMS     (  911): releaseWL(43f902c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4521): JXcore Cordova bridge is ready!
I/jxcore-log( 4521): 
,W/jxcore-log( 4521): JXcore engine is started
,I/chromium( 4521): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4521): Toggling radios to true
I/jxcore-log( 4521): 
,D/BluetoothAdapter( 4521): enable(): BT is already enabled..!
,D/WifiManager( 4521): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  911): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  911): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  911): Settings:Agentvalue: 2
,W/Settings:Agent(  911): >> traceCallingStack()
D/WifiService(  911): setWifiEnabled: true pid=4521, uid=10389
E/WifiService(  911): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  911): isSprintWifiRestricted(): false
I/WifiService(  911): isMdmWifiRestricted(): false
D/WifiService(  911): New client listening to asynchronous messages
,D/WifiSettingsStore(  911): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  911): Process.myPid(): 911
W/Settings:Agent(  911): Process.myTid(): 1216
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
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  911): 
W/Settings:Agent(  911): << traceCallingStack(): 4(ms)
D/WifiManager( 4521): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  911): doBoolean: DISCONNECT
D/WifiManager( 4521): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): TDLS: Tear down peers
I/wpa_supplicant( 1179): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4521): Radios toggled
I/jxcore-log( 4521): 
I/jxcore-log( 4521): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4521): 
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1179): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1179): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  911): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): TDLS: Remove peers on disassociation
D/HTCRequest(  911): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  911): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  911): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/HTCRequest(  911): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb84bbbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1179): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  911): WifiMonitor:getReasonFromEventString() 3
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  911): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  911): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1179):, State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  911):    returned true
D/WifiPerfLock(  911): release()
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  911): PerfLock released for exiting ConnectedState
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  911):    returned true
D/ConnectivityService(  911): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  911): acquireWL(446571c0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 911 1000 null
D/WifiP2pService(  911): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/DhcpStateMachine(  911): [RunningState] Stop DHCP
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  911): doBoolean: RECONNECT
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20813 mDataStallAlarmIntent=PendingIntent{42c35878: PendingIntentRecord{42bbe4a8 android broadcastIntent}}
D/WifiP2pService(  911): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): Fast associate: Old scan results
I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  911):    returned true
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateMachine(  911): Enter handleNetworkDisconnect
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  911): isAvailable+-
D/UsbnetStateTracker(  911): reconnect
,D/UsbnetStateTracker(  911): isAvailable+-
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  911):    returned true
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  911): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  911): default: reconnect()
D/MDST    (  911): default: setTeardownRequested(false)
D/MDST    (  911): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  911): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WISPrService( 3858): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  911): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  911): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  911): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  911): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 3858): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiService(  911): New client listening to asynchronous messages
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): handleConnectivityChange: resetting
,D/ConnectivityService(  911): resetConnections(wlan0, 3)
,V/NativeCrypto( 1354): Read error: ssl=0x6607a540: I/O error during system call, Connection timed out
D/libc    (  364): [NET] entry_id:3   entry:0xb71488e0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb714d190  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb714d348  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb714d428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb714d090  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb714d4f0  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7148fe8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,V/NativeCrypto( 1354): SSL shutdown failed: ssl=0x6607a540: I/O error during system call, Broken pipe
D/ConnectivityService(  911): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  911): acquireWL(43b612c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/WISPrService( 3858): >>>>>WISPrService start isConnected = false<<<<<
D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3858): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  911): acquireWL(43e21db8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  911): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  911): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/WifiStateMachine(  911): startScan Pid: 911 Uid 1000
,D/WifiNative-wlan0(  911): doBoolean: SCAN
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1179): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
,I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  911):    returned false
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/ConnectivityService(  911): reportInetCondition for net -1, percentage: 0 by  (1354/10029)
D/BatSI   (  911): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/PMS     (  911): releaseWL(43b612c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/PMS     (  911): releaseWL(43e21db8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  911): mActiveDefaultNetwork: -1
D/ConnectivityService(  911): handleInetConditionChange: no active default network - ignore
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (3938/10154)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  911): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  911): NoActiveNetworkState
,I/NetworkMonitor( 3938): type=WIFI subType= reason=null isConnected=false
D/Tethering(  911): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  911): bSetPropertyMultiRAB:false
D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  911): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/Tethering(  911): ipv4Default null
,I/Tethering(  911): No IPv4 upstream interface, giving up.
D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
,D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1264): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/PMS     (  911): acquireWL(44ac4828): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4373/10100)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1559/10029)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10076)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4373/10100)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2387/10021)
,D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  911): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  911): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4574 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/PMS     (  911): releaseWL(44ac4828): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4574): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4574): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4574): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4574): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4574): Preparing secondary program dexes.
V/DexLibLoader( 4574): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4574): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4574): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4574): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4574): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4574): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4574): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4574): Dex already copied
D/OdexVerifier( 4574): Odex verification is skipped.
,V/DexLibLoader( 4574): Creating class loader
V/DexLibLoader( 4574): Finished creating class loader
V/DexLibLoader( 4574): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4574): Dex already copied
D/OdexVerifier( 4574): Odex verification is skipped.
V/DexLibLoader( 4574): Creating class loader
V/DexLibLoader( 4574): Finished creating class loader
V/DexLibLoader( 4574): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4574): Dex already copied
D/OdexVerifier( 4574): Odex verification is skipped.
V/DexLibLoader( 4574): Creating class loader
V/DexLibLoader( 4574): Finished creating class loader
V/DexLibLoader( 4574): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4574): Dex already copied
D/OdexVerifier( 4574): Odex verification is skipped.
V/DexLibLoader( 4574): Creating class loader
V/DexLibLoader( 4574): Finished creating class loader
V/DexLibLoader( 4574): Verifying classes from secondary dexes.
,D/DexLibLoader( 4574): DexLibLoader.ensureDexLoaded took 18 ms
,W/dalvikvm( 4574): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4574): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4574): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4574): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4574): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4574): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4574): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4574): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1179): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
I/wpa_supplicant( 1179): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1179): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1179): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=9 entropy=0
D/wpa_supplicant( 1179): Add randomness: count=10 entropy=1
D/wpa_supplicant( 1179): Add randomness: count=11 entropy=2
D/wpa_supplicant( 1179): Add randomness: count=12 entropy=3
D/wpa_supplicant( 1179): Add randomness: count=13 entropy=4
D/wpa_supplicant( 1179): Add randomness: count=14 entropy=5
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1179): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 3
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 1
I/wpa_supplicant( 1179): wpa_s->is_screen_on 1
I/wpa_supplicant( 1179): wpa_s->i,fname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): selected network = 2
D/wpa_supplicant( 1179): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84bd4e8  current_ssid=0x0
D/wpa_supplicant( 1179): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1179): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1179): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1179): check if in concurrent case
I/wpa_supplicant( 1179): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1179): RSN: PMKSA cache search - network_ctx=0xb84bd4e8 try_opportunistic=0
D/wpa_supplicant( 1179): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1179): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1179): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1179): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1179): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1179): nl80211: Unsubscribe mgmt frames handle 0xb84bc718 (mode change)
D/wpa_supplicant( 1179): nl80211: Subscribe to mgmt frames with non-AP handle 0xb84bc718
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718,
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb84bc718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1179):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1179):   * freq=2412
D/wpa_supplicant( 1179):   * Auth Type 0
D/wpa_supplicant( 1179):   * WPA Versions 0x2
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1179): nl80211: Connect request send successfully
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING,
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1179): reply (779) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220,
I/wpa_supplicant( 1179): level=-45
I/wpa_supplicant( 1179): tsf=0000000106491436
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000106491449
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1179): ssid=01ABC
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=2
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000106491452
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=3
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2452
I/wpa_supplicant( 1179): level=-86
I/wpa_supplicant( 1179): tsf=0000000106491463
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1179): freq=2437
I/wpa_supplicant( 1179): level=-89
I/wpa_supplicant( 1179): tsf=0000000106491455
I/wpa_supplicant( 1179): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=UPC Wi-Free
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=5
I/wpa_supplicant( 1179): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1179): freq=2437
I/wpa_supplicant( 1179): level=-90
I/wpa_supplicant( 1179): tsf=0000000106491459
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=UPC5999698
I/wpa_supplicant( 1179): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (6) end of scan result ==
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 106491436, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 106491449, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 106491452, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 106491463, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 106491455, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 106491459, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 6 to mScanResults
D/BatSI   (  911): WIFI scan stopped for: 640a0300 uid:1000
D/WifiManager( 1218): getScanResults enter 
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (6) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@429cb240
,W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  911): Couldn't get kernel wake lock stats
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  911): setLight #0: color=#0
W/SensorService(  911): pid=911, uid=1000
W/dalvikvm( 4574): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@429cb240, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426f6850
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@42bf0750
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  911): mWirelessDisplayManager is null
,D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Connect event
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1179): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1179): Add randomness: count=15 entropy=6
I/wpa_supplicant( 1179): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): TDLS: Remove peers on association
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1179): EAPOL: enable timer tick
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1179): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1179): Get randomness: len=32 entropy=7
D/WifiMonitor(  911): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  911): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  911): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  911): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  911): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  911): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantSt,ateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  911): Enter handleAssociatedWithEvent
D/WifiStateMachine(  911): Associated
D/WifiStateMachine(  911): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  911): Exit handleAssociatedWithEvent
D/WifiStateMachine(  911): BSSID was changed, update WiFi database
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  911): interfaceStatusChanged wlan0, true
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  911): This record is existed, only update it...
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb84bc9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ee5b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1179):    broadcast key
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1179): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1179): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1179): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1179): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1179): set send_ind_to_ndc = 0
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1179): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1179): EAPOL authentication completed successfully
I/wpa_supplicant( 1179): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
D/Tethering(  911): interfaceStatusChanged wlan0, true
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  911): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/WifiStateMachine(  911): fetchFrequency(), freq = 2412
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  911): This record is existed, only update it...
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): mActiveDefaultNetwork: -1
D/WISPrService( 3858): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3858): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/FbInjectorInitializer( 4574): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/DhcpStateMachine(  911): [StoppedState] Start DHCP
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiStateMachine(  911): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  911): acquireWL(43f769c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 911 1000 null
,D/WifiStateMachine(  911): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 1
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  911):    returned null
E/WifiStateMachine(  911): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  911):    returned null
D/WifiP2pService(  911): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42c0cda8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42c0cda8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4574): Verify
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 332ms
D/NfcService( 1248): ScreenObserver: OFF
V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@44566818)
,D/NfcService( 1248): applyRouting - 0
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
D/PMS     (  911): OOBE c monitor 11
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
I/InputMethodManagerService(  911): Disable input method client, pid=4521
D/PMS     (  911): acquireWL(44a49418): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1248 1027 null
D/PMN     (  911): wakingUp
,D/NfcService( 1248): applyRouting -2
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  911): releaseWL(44a49418): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  911): No lock screen! windowToken=null
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
D/PMN     (  911): onScreenOn
,I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1248): applyRouting - 0
D/MtpService( 2387): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2387): [MTP][onReceive]-
D/WifiService(  911): New client listening to asynchronous messages
D/PMS     (  911): acquireWL(42ce2040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/NfcService( 1248): applyRouting -2
D/PMS     (  911): releaseWL(42ce2040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): acquireWL(43d4a7b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1248 1027 null
D/PMS     (  911): releaseWL(43d4a7b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1547): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1179): Change stage from stage0 to stage3
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): SET_SCREEN_ON:On
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  911):    returned true
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  911): updateScreenOn: false
,W/fb4a(:<default>):BaseAnalyticsConfig( 4574): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4574): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/ClockThread( 1113): stop update clock
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1547): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): acquireWL(4404da40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(4404da40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43cc0d08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4574): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1743): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): onScreenOn: 1452860423056
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1743): onScreenOn: 1452860423056
D/PMS     (  911): releaseWL(43cc0d08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  911): killProcessQuiet, pid=4308
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426f6850
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426f6850, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@42bf0750
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  911): Killing 4308:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/PMN     (  911): goingToSleep
I/ActivityManager(  911): Recipient 4308
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  911): Client connection lost with reason: 4
D/PMS     (  911): acquireWL(43f782f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
,D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20814 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): SET_SCREEN_ON:Off
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1179): get_ip_address source addr = 02000000
I/wpa_supplicant( 1179): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  911):    returned true
I/AlarmManager(  911): [AlarmQueuing] wifi connection: true
D/PMS     (  911): acquireWL(44aae228): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
,D/PMS     (  911): releaseWL(44aae228): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
V/SRS_Proc(  371): ParamSet string: screen_state=off
D/AutoSetting( 1337): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  911): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4608 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1337/10055)
,D/NetworkPolicy(  911): updateScreenOn: false
,D/AutoSetting( 1337): Util - no network available!
,D/ContactMessageStore( 1233): start background delete task...
D/ContactMessageStore( 1233): size: 0 , 0
,D/ContactMessageStore( 1233): Background delete complete
D/AutoSetting( 1337): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1337): service - mHandler: cancel location update
,D/AutoSetting( 1337): service -           changes count: 0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1337/10055)
,W/fb4a(:<default>):UserScope( 4574): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4574): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4574): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/AutoSetting( 1337): service - mHandler: cancel location update
,D/AutoSetting( 1337): service -           changes count: 0
,D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/MobileConnectivityChangeReceiver( 4608): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4608): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4608): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4608): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/DotMatrix( 1547): [EventService] getTotalRam: 1873 Mb
,I/ActivityManager(  911): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4624 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=3896
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 3896:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/PMS     (  911): acquireWL(43f5f290): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(43f5f290): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4608/10079)
D/PMS     (  911): acquireWL(44a19420): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4608/10079)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4608/10079)
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1743): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): disableBatteryAlarm: null
,D/PMS     (  911): releaseWL(44a19420): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1743): onScreenOff
,I/ActivityManager(  911): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4638 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=4187
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 4187:com.google.android.talk/u0a111 (adj 15): empty #17
,I/dalvikvm-heap( 4574): Grow heap (frag case) to 9.955MB for 84664-byte allocation
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4574): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4574): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4574): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4574): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
W/ContextImpl( 4638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4638): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  911): Recipient 3896
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4574): Grow heap (frag case) to 9.971MB for 28144-byte allocation
E/dalvikvm( 4574): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4574): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4574): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4574): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4574): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4574): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4574): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4574): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4574): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4574): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4574): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4574): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4574): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4574): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4574): Grow heap (frag case) to 10.012MB for 39954-byte allocation
,I/ActivityManager(  911): Recipient 4187
,I/dalvikvm-heap( 4574): Grow heap (frag case) to 10.088MB for 79892-byte allocation
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4638/10151)
,V/WebViewChromiumFactoryProvider( 4638): Binding Chromium to main looper Looper (main, tid 1) {422501a0}
,I/LibraryLoader( 4638): Expected native library version number "",actual native library version number ""
,I/chromium( 4638): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4638): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4638): BLUETOOTH permission is missing!
D/PMS     (  911): acquireWL(42e1e938): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): acquireWL(44665a60): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): releaseWL(42e1e938): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4638): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4638): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4638): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4638): Local Branch: 
I/Adreno-EGL( 4638): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4638): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4638):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4638): Starting up...
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4638/10151)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4638/10151)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4094/10160)
,I/dalvikvm-heap( 4574): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/Process (  911): killProcessQuiet, pid=4342
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4094/10160)
I/ActivityManager(  911): Killing 4342:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4342
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,I/iu.Environment( 2181): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2181): num queued entries: 0
,I/iu.UploadsManager( 2181): num updated entries: 0
,I/iu.SyncManager( 2181): NEXT; no task
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44afe868 u0 ReceiverList{43dc8be8 4574 com.facebook.katana/10027/u0 remote:42d5f130}}
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44afe868 u0 ReceiverList{43dc8be8 4574 com.facebook.katana/10027/u0 remote:42d5f130}}
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43cc1068 u0 ReceiverList{43cc1008 4574 com.facebook.katana/10027/u0 remote:4499b520}}
,D/AutoSetting( 1337): receiver - intent: android.intent.action.USER_PRESENT
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
W/ActivityManager(  911): Activity pause timeout for ActivityRecord{43dc3098 u0 com.test.thalitest/.MainActivity t2}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
D/AutoSetting( 1337): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3858): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3858): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3858): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3858): Cust_ConnectToPC   : spcsc>false
D/        ( 3858): Cust_ConnectToPC   : IPT>true
D/        ( 3858): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3858): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3858): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3858): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3858): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3858): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3858): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3858): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3858):  defaultType:0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
W/ContextImpl( 3858): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/wpa_supplicant( 1179): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1179): EAPOL: disable timer tick
I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4678 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  911): acquireWL(42e6d4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/PMS     (  911): releaseWL(42e6d4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4574): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4574): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4574): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4678): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  911): acquireWL(43b217a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4678 1000 null
D/SmartSyncUtils( 4678): isEpsOn(), nState = 0
,D/PMS     (  911): releaseWL(43b217a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4678): getMobilePolicyEnabled, result = true
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  911): killProcessQuiet, pid=4373
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4373:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4373
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4678): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4678): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4678): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4678): isEpsOn(), nState = 0
D/WifiService(  911): New client listening to asynchronous messages
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42bf0750
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
,W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42bf0750, eanble = 0, strlen(mName) = 36
,W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42bf0750, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42bf0750
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42b7bdb0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42b7bdb0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/Choreographer( 4521): Skipped 238 frames!  The application may be doing too much work on its main thread.
,D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ResourceType( 4521): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4521): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42259140 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  911): releaseWL(43f782f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4521): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
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
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  911):    returned true
D/WifiStateMachine(  911): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL,
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  911): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler },
,D/PMS     (  911): releaseWL(43f769c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): gateway: /192.168.1.1
,D/WifiNative-wlan0(  911): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1179): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  911):    returned true
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  911): VerifyingLinkState enter
D/WifiStateMachine(  911): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  911): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  911): VerifyingLinkState: enableIpv6,
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  911): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  911): default: teardown()
,D/WifiWatchdogStateMachine(  911): WAN detection
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/MDST    (  911): default: setTeardownRequested(true)
V/NetworkPolicy(  911): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/MDST    (  911): default: setEnableApn apnType =default , enable=false
D/MDST    (  911): default: setTeardownRequested(true)
D/ConnectivityService(  911): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  911): Unexpected mtu value: android.net.wifi.WifiStateTracker@42bd1958
,D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3858): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  911): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiStateMachine(  911): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  911): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  911): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  911): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  911): handleConnectivityChange: resetting
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  911): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  911): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  911): acquireWL(44a263e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4608/10079)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/WirelessDisplayService(  911): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  911):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1113): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  911): acquireWL(44aafc20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44af8dc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(44aafc20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2181): Checkin interval check for package: unspecified last checkin: 1452860374461 min interval config: 0 actual interval: 49990
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/CheckinService( 2181): Checking schedule, now: 1452860424458 next: 1452860404432
,I/CheckinService( 2181): active receiver: enabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2181, uid=10029, userID:0
,D/ConnectivityService(  911): mActiveDefaultNetwork: WIFI
,I/CheckinService( 2181): Preparing to send checkin request
,I/EventLogService( 2181): Accumulating logs since 1452860370938
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/PMS     (  911): releaseWL(44a263e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2181): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2181): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2181/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  911): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4731 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4731): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4731): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4731): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4731): install
,I/MultiDex( 4731): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4731): loading existing secondary dex files
,I/MultiDex( 4731): load found 3 secondary dex files
,I/MultiDex( 4731): install done
,W/dalvikvm( 4731): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4731): VFY: unable to resolve instance field 36
,W/dalvikvm( 4731): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4731): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4731): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4731): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4731): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4731): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4731): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4731): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4731): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4731): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/WearableService( 1218): callingUid 10029, callindPid: 1218
,E/MDM     ( 1218): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2181): Restart initialization of location
,W/GCoreFlp( 1218): No location to return for getLastLocation()
,W/FusedLocationProvider( 1218): location=null
D/PMS     (  911): acquireWL(44aaea00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
D/PMS     (  911): releaseWL(44aaea00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AuthorizationBluetoothService( 1354): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1354): Proximity feature is not enabled.
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4731): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3667646807
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1244302899
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/PMS     (  911): releaseWL(446571c0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  911): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
,D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  911): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0,
,I/Adreno-EGL( 4731): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4731): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4731): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4731): Local Branch: 
I/Adreno-EGL( 4731): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4731): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4731):                  aa63bbd948f41d15fc72f585e
D/PMS     (  911): acquireWL(44168288): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1559/10029)
D/PMS     (  911): releaseWL(44168288): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,D/CaptivePortalTracker(  911): NoActiveNetworkState
V/Tethering(  911): bSetPropertyMultiRAB:false
D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
I/Tethering(  911): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  911): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  911): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  911): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  911): Found interface wlan0
,D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0],
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(42d7bcc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/NetworkMonitor( 3938): type=WIFI subType= reason=null isConnected=true
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/WifiStateMachine(  911): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
D/libc    (  911): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (3938/10154)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.musicenhancer (3973/10053)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4608/10079)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10076)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ConnectivityHelper( 1264): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1559/10029)
D/PMS     (  911): releaseWL(42d7bcc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(42ddb150): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  911): releaseWL(42ddb150): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1321): Unsupported attribute readOnly
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2387/10021)
,W/Settings( 4731): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/AutoSetting( 1337): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1337): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/MobileConnectivityChangeReceiver( 4608): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1337): service - onStartCommand() screen is off, don't request location
,D/MobileConnectivityChangeReceiver( 4608): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1337/10055)
D/AutoSetting( 1337): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1337): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1337/10055)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4638/10151)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4094/10160)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4094/10160)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/CheckinService( 2181): Checkin interval check for package: unspecified last checkin: 1452860374461 min interval config: 0 actual interval: 51229
D/PMS     (  911): acquireWL(44a67298): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(44a67298): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4094): Grow heap (frag case) to 13.517MB for 1821008-byte allocation
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2181, uid=10029, userID:0
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2181): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2181): num queued entries: 0
,I/iu.UploadsManager( 2181): num updated entries: 0
,I/iu.SyncManager( 2181): NEXT; no task
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/PMS     (  911): acquireWL(449abb00): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/libc    ( 1354): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1354): [NET] getaddrinfo-,err=8
D/libc    ( 1354): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1354): [NET] getaddrinfo-, 1
D/libc    ( 1354): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b8b6 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 177
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1354): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (4731/10029)
,I/Adreno-EGL( 4731): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4731): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4731): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4731): Local Branch: 
I/Adreno-EGL( 4731): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4731): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4731):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
D/libc    ( 1354): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1354): [NET] getaddrinfo-,err=8
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
W/fb4a(:<default>):UserScope( 4574): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4574): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/Adreno-EGL( 4731): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4731): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4731): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4731): Local Branch: 
I/Adreno-EGL( 4731): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4731): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4731):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1354): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1354): [NET] getaddrinfo-,err=8
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/PMS     (  911): acquireWL(43f86c48): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,D/PMS     (  911): releaseWL(449abb00): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1354/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
,D/PMS     (  911): releaseWL(43f86c48): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42e9a940): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1354/10029)
,D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1354/10029)
,D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
,E/fb4a(:<default>):LocalFbBroadcastManager( 4574): Called registerBroadcastReceiver twice.
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
D/PMS     (  911): releaseWL(42e9a940): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4574/10027)
,I/CheckinRequestBuilder( 2181): Classify the device as Phone.
,D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2181): [NET] getaddrinfo-,err=8
D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2181): [NET] getaddrinfo-, 1
,D/libc    ( 2181): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =bfb1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 63
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2181): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2181): [NET] getaddrinfo-,err=8
,D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2181): [NET] getaddrinfo-,err=8
D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2181): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2181): Sending checkin request (12251 bytes)
,D/PMS     (  911): releaseWL(44665a60): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=5 [20][1][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2181): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2181): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2181/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,I/CheckinRequestBuilder( 2181): Classify the device as Phone.
,I/CheckinTask( 2181): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2181): Checking schedule, now: 1452860426944 next: 1453383363938
,I/CheckinService( 2181): active receiver: disabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2181, uid=10029, userID:0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,I/CheckinService( 2181): Checking schedule, now: 1452860426985 next: 1453383363938
,I/CheckinService( 2181): active receiver: disabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2181, uid=10029, userID:0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
,D/CheckinService( 2181): Recording last checkin time for package unspecified as 1452860426992
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(44af8dc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,D/GCM     ( 1354): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
D/libc    (  911): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  364): [NET] +++++ res_nsend xid =817d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  911): Find DNS Address www.htc.com/104.81.130.175,
,I/GAV2    ( 4638): Thread[GAThread,5,main]: No campaign data found.
,D/ContactMessageStore( 1233): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1233): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4396
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4396:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4396
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  911): killProcessQuiet, pid=4360
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4360:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4360
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1337): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1337): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1337): service - requestNLP() NetworkLocationProvider not enabled
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  911): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4783 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1264): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1248): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1264): Deferring update until onResume
,D/Launcher( 1264): waitUntilResume // bindAppsUpdated
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,E/ExternalAccountType( 1321): Unsupported attribute readOnly
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
,D/PhoneApp( 1233): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4783): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4783): MmsConfig.loadMmsSettings
,W/dalvikvm( 4783): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4783): VFY: unable to resolve instance field 36
,W/dalvikvm( 4783): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4783): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  911): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4806 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4783, uid=10111, userID:0
,W/Settings( 4783): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4806): onCreate
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4783, uid=10111, userID:0
,V/GetPrviateResource( 4806): GetPrviateResource
,V/GetPrviateResource( 4806): GetPrviateResource
,D/MmsCustomizationProvider( 4806): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4783, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4783, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4783, uid=10111, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4783, uid=10111, userID:0
,D/PMS     (  911): acquireWL(42d3f3c8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4783 10111 null
D/MmsCustomizationProvider( 4806): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4783): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4783): MmsConfig.loadFromDatabase
,E/Babel   ( 4783): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4783): MmsConfig.loadFromResources
,E/Babel   ( 4783): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4783): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/[PluginManager]RegisterService( 1337): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1337): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2873): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(44206100): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(43a20538): PARTIAL_WAKE_LOCK  AsyncService 0x1 4094 10160 null
,W/PackageManager(  911): Unable to load service info ResolveInfo{43f8f7d0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PMS     (  911): releaseWL(44206100): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 4783): Installed default security provider GmsCore_OpenSSL
I/dalvikvm-heap( 4094): Grow heap (frag case) to 15.215MB for 1821008-byte allocation
D/PMS     (  911): acquireWL(44592960): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(43a20538): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/MessageCustFlag( 4806): sense_version=6.0
D/BTAccessoryUtil( 4806): createReceiver
D/PMS     (  911): releaseWL(42d3f3c8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/BTAccessoryUtil( 4806): registerReceiver return intent = null
D/MessageCustFlag( 4806): sku_id=99
W/SystemReader( 4806): Cannot find message_ambs_application_id, use default value instead
D/Messaging( 4806): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4806): networkCode: 
D/MessageCustFlag( 4806): sku_id=99
D/MmsConfig( 4806): SIE smsPri: null
D/MmsConfig( 4806): networkCode: 
I/dalvikvm-heap( 4094): Grow heap (frag case) to 16.947MB for 1821008-byte allocation
,I/ActivityManager(  911): Resuming delayed broadcast
D/HtcTelephonyCapability( 4806): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4806): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4806): getRATByHtcTelephonyCapability:1
W/SystemReader( 4806): Cannot find qct_8960_interface, use default value instead
,D/Process (  911): killProcessQuiet, pid=4414
,I/ActivityManager(  911): Killing 4414:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PackageBroadcastService( 2181): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  911): Recipient 4414
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageBroadcastService( 2181): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  911): Resuming delayed broadcast
,I/Icing   ( 2181): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  911): start
,I/GCoreNlp( 1218): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  911): applying state to connected service
,D/LocationProviderProxy(  911): applying state to connected service
D/PMS     (  911): acquireWL(44a56100): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(44a56100): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(439833b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(439833b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43cf81a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43cf81a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2873): UpdateCorporaTask done [took 513 ms] updated apps [took 513 ms] 
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  911): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Process (  911): killProcessQuiet, pid=3973
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3973:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3973
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1264): loadItems() com.htc.launcher.pageview.WidgetManager@422ddc68 +
,I/Prism.WidgetManager( 1264): onLoadItems() +
,I/Icing   ( 2181): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2181): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  911): releaseWL(44592960): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1264): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1264): onLoadItems() -
,I/Prism.ItemManager( 1264): loadItems() com.htc.launcher.pageview.WidgetManager@422ddc68 -
,D/PhoneApp( 1233): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1233): -- N1 =0
,D/PhoneApp( 1233): -- N2 =0
,D/PhoneApp( 1233): -- N3 =0
,D/Messaging( 4806): mNeedToUpdateDate2 start
,D/MmsConfig( 4806): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4806): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4806): 
D/MmsAsyncWorkHandler( 4806): HM tk = 20001
D/ReportIndicatorCache( 4806): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4806): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@42252470
,I/Messaging( 4806): mccmnc> 
D/DraftCache( 4806): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4806): [DraftCache/1] refresh
,D/MmsConfig( 4806): networkCode: 
D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1233):  phoneType = -1
D/MmsSmsV2Provider( 1233): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4806): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/PhoneStorageUtil( 4806): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4806): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4806): createReceiver
D/MmsSmsV2Provider( 1233):  phoneType = -1
,D/MmsSmsV2Provider( 1233): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 4806): sense_version=6.0
,D/Jerry   ( 4806): start to preload cursor >>>>>>>
,D/Messaging( 4806): mNeedToUpdateDate2: false
,D/TelephUtils( 1233): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,V/MmsProvider( 1233): Update uri=content://mms, match=0
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1233):  phoneType = -1
,V/MmsProvider( 1233): selection=st=129 AND m_type!=134
,D/Messaging( 4806): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4806): TransactionService is going to be woken up.
D/Messaging( 4806): ViewCache CreatePreload
,D/Messaging( 4806): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4806): _has_set_default_values_2=true
,V/TransactionService( 4806): 1-Creating TransactionService
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
D/MmsSmsV2Provider( 1233):  phoneType = -1
,D/MmsSmsV2Provider( 1233): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MsgPreferenceUtils( 4806): def_index: 0
V/TransactionService( 4806): onStartCommand: 1
,D/MmsSystemEventReceiver( 4806): unRegisterForConnectionStateChanges
V/TransactionService( 4806): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4806): Loading previous transactions.
,D/MsgPreferenceUtils( 4806): globalIndex = 1
,D/MsgPreferenceUtils( 4806): phone state: true
D/MsgPreferenceUtils( 4806): sd state: false
,D/MsgPreferenceUtils( 4806): vIndex = 0
D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1233): sku_id=99
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1233): device_type: 1
,D/DraftCache( 4806): [DraftCache/481] rebuildCache
,D/TransactionService( 4806): Force set service start id to 1
V/TransactionService( 4806): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4806): unRegisterForConnectionStateChanges
,D/TransactionService( 4806): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4806): Destroying TransactionService
D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1233):  phoneType = -1
,D/MmsSmsV2Provider( 1233): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,V/TransactionService( 4806): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/Jerry   ( 1233): URI_DRAFT
,D/Messaging( 4806): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/DraftCache( 4806): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4806): [DraftCache/481] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4806): 
D/MmsAsyncWorkHandler( 4806): HM tk = 20002
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1233): sku_id=99
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/AccFlag ( 1233): sku_id=99
,I/GAV4    ( 4783): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(43d0f0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  911): n_update end
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1547): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(43d0f0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(449cc308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{42b8ffe8: PendingIntentRecord{42d9b418 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126956, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{42d662a0: PendingIntentRecord{42dbf418 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137207, Int=0
,D/PMS     (  911): acquireWL(439f13c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(44aa6768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(44aa6768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(439f13c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,D/PMS     (  911): acquireWL(43388990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(449cc308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(43388990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43bcde00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): acquireWL(43bd2d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44aa3948): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43bcde00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PerfProfileCollectorService( 2181): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 2181): removeStateFiles() called
,D/PerfProfileCollectorService( 2181): User is not opt-in to Usage & Diagnostics.
D/PMS     (  911): releaseWL(43bd2d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(44aac700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(44aa3948): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(44aac700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44a67298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(44a67298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44a3aaf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(44a3aaf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1337): service - mHandler: update timezone
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1497): service - onCreate()
,D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  911): batLight: Full, plugged
,D/DotMatrix( 1547): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1547): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1497): service - mHandler: update timezone
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1337): service - handleMessage() stop self
,D/AutoSetting( 1497): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1497): service - showManualTimeZoneSelector() send notification (single)
,D/AutoSetting( 1337): service - handleMessage() quit looper
,D/AutoSetting( 1337): service - onDestroy() END
,D/DotMatrix( 1547): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1547): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{422a9bc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 2 7 2 11
,D/PMS     (  911): acquireWL(43f7d358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{427411b0: PendingIntentRecord{42a577f8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142248, Int=0
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(43f75d08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(43f7d358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1dd3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 3
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo_proxy-, success
,I/global  (  911): call createSocket() return a new socket.
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x35342e3234302e),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  911): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  911): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  911): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  911):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  911): acquireWL(432785b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=143969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(432785b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  911): killProcessQuiet, pid=4449
,I/ActivityManager(  911): Killing 4449:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 4449
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): releaseWL(43f75d08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1233): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1233): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{44ac2b00 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  911): acquireWL(42baf6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1547): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(42baf6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4463
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4463:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4463
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(42d9d2e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10027}
,V/AlarmManager(  911): sending alarm PendingIntent{42f61b58: PendingIntentRecord{444dca08 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175379, Int=0
,D/PMS     (  911): releaseWL(42d9d2e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1233): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(42c58cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{43f78ae0: PendingIntentRecord{42d9b418 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186989, Int=0
,D/PMS     (  911): acquireWL(42b95978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42c58cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=6 [33][2][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(42b7afc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42b7afc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42b95978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42cdb4c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(42cdb4c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42b247c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0,
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0],
,D/PMS     (  911): acquireWL(42bafa28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1218): Vacuum at: now=1452860503328 tag=VacuumService
,D/PMS     (  911): acquireWL(42cb1028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42bafa28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42b247c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42dcbdb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
D/PMS     (  911): releaseWL(42dcbdb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42c3ba60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(42c3ba60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1218): Scheduling Phenotype for one-off execution 3354 seconds from now (1452860503746)
,D/GetConfigurationSnapshotOperation( 1218): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1218): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1218): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/libc    ( 1218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1218): [NET] getaddrinfo-,err=8
,D/libc    ( 1218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1218): [NET] getaddrinfo-, 1
D/libc    ( 1218): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9460 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 245
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1218): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1218): [NET] getaddrinfo-,err=8
,D/libc    ( 1218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1218): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=37 [8][3][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(42cb1028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43aae898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(43aae898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42b65488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(42b65488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(439adca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(439adca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4337a510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=203970, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4337a510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43d44238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1547): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(43d44238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): runPSCheck
,D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(44592830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44592830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(4403b0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=263969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4403b0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4405f8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4405f8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(44ac5af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=323969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44ac5af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(44a944c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44a944c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(43db7428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=383969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43db7428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(42c7bd88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42c7bd88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(44ad5268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=443969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44ad5268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42a5d150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/PMS     (  911): releaseWL(42a5d150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1547): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(440b1870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(440b1870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(4326bbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=503969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4326bbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(43f81658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43f81658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1547): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43b21800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=563970, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43b21800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42cd5d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42cd5d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(44a82218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44a82218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1233): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1233): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1233): sku_id=99
D/ContactMessageStore( 1233): start background delete task...
,D/ContactMessageStore( 1233): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1233): size: 0 , 0
,D/ContactMessageStore( 1233): Background delete complete
,D/PMS     (  911): acquireWL(43ff2d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=623969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43ff2d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  911): killProcessQuiet, pid=4164
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4164:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4164
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(42e96608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42e96608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43fac530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=683969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43fac530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42ccd198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42ccd198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43e7ddb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=743970, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43e7ddb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(440c7f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(440c7f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(44022780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=803970, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44022780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(44663b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44663b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42c5b020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=863969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42c5b020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(44a702f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44a702f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(433799b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=923970, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(433799b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43cdb330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43cdb330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(440b1060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=983969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(440b1060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,D/PMS     (  911): acquireWL(449cbc68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{424c51f8: PendingIntentRecord{42bdc110 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=787870, Int=0
,I/ActivityManager(  911): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4900 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  911): sending alarm PendingIntent{4237f5f0: PendingIntentRecord{42d39c98 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452860528325, Int=10800000
,V/AlarmManager(  911): sending alarm PendingIntent{43dbdbb0: PendingIntentRecord{42e58200 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452861109103, Int=1800000
D/ConnectivityService(  911): Done.
,D/ConnectivityService(  911): Setting timer for 720seconds
,V/AlarmManager(  911): sending alarm PendingIntent{42ce3170: PendingIntentRecord{42ca69b0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452861248710, Int=900000
,V/AlarmManager(  911): sending alarm PendingIntent{42ca7288: PendingIntentRecord{44657a70 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452861323838, Int=0
,D/PMS     (  911): acquireWL(44a90328): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44a26940): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4678): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  911): releaseWL(44a90328): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 4678): call getInstance()
,D/SmartSyncUtils( 4678): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4678): MY_DEBUG = false
,D/PMS     (  911): acquireWL(436463a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4678 1000 null
,I/EventLogService( 2181): Aggregate from 1452860424488 (log), 1452859308954 (data)
,D/PMS     (  911): releaseWL(449cbc68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4678): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4678): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4678): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4678): SettingOnTime = 1452924000000, randomSettingOnTime = 1452923454000
D/SmartSyncScreenOnOffTimeReceiver( 4678): SettingOffTime = 1452909600000, randomSettingOffTime = 1452912523000
,D/SmartSyncScreenOnOffTimeReceiver( 4678): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4678): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4678): bNightModeTurnOffOnce = false
W/BatSI   (  911): Couldn't get kernel wake lock stats
D/PMS     (  911): releaseWL(436463a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.aurora (4900/10049)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(44a26940): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/Process (  911): killProcessQuiet, pid=4492
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4492:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4492
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(44a69bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{42d3d268: PendingIntentRecord{42ea1100 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1009995, Int=0
,D/PMS     (  911): acquireWL(44a674f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(44a674f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(44a69bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44a3aaf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=23 [78][18][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): acquireWL(44a1dbc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,I/GoogleURLConnFactory( 1218): Using platform SSLCertificateSocketFactory
D/PMS     (  911): releaseWL(44a3aaf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PhenotypeConfigurator( 1218): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/PMS     (  911): acquireWL(4466a1e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(4466a1e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1218): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1218): [NET] getaddrinfo-,err=8
D/libc    ( 1218): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1218): [NET] getaddrinfo-, 1
,D/libc    ( 1218): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =26a7 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 16892
D/libc    (  364): [NET]res_nsend:resplen=45
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1218): [NET] getaddrinfo_proxy-, success
D/PMS     (  911): acquireWL(44465a88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1354/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1354/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(44465a88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=8 [23][2][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/libc    ( 1218): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1218): [NET] getaddrinfo-,err=8
D/libc    ( 1218): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1218): [NET] getaddrinfo-,err=8,
,W/PhenotypeConfigurator( 1218): Server returned 404
D/PMS     (  911): releaseWL(44a1dbc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(42b5e338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024742
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024845
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024852
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024856
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024862
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026360
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026372
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029318
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360030901
,D/PMS     (  911): releaseWL(42b5e338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4250ef28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4250ef28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(422eeaf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1043970, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(422eeaf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42bd5f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42bd5f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42b02f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1103970, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42b02f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(427b6770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(427b6770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43d139b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1163969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43d139b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42d3d8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42d3d8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(42bf1e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1223969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42bf1e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(424996a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{4247d5f0: PendingIntentRecord{42c42af0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1259973, Int=0
,D/PMS     (  911): acquireWL(43e7e570): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(42d204c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(424996a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): releaseWL(43e7e570): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  911): releaseWL(42d204c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  911): acquireWL(42e524e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42e524e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42d1cde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1283969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1264): Grow heap (frag case) to 12.641MB for 50416-byte allocation
D/PMS     (  911): releaseWL(42d1cde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42b76c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42b76c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(427d62b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1343969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(427d62b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42b9fea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42b9fea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4294c030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1403969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4294c030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43265af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43265af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42d2afe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1463969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42d2afe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42bbd3a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42bbd3a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4255dfa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1523970, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4255dfa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43689538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43689538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42d22188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1583970, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42d22188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42baac08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42baac08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43e21488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1643969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1264): Grow heap (frag case) to 12.641MB for 50416-byte allocation
,D/PMS     (  911): releaseWL(43e21488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42c95c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42c95c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43d3b280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1703969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43d3b280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42d89838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
I/BatteryService(  911): n_update end
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(42d89838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
,D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1547): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1547): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42e33e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42e33e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42cebb90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1763969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42cebb90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/PMS     (  911): acquireWL(42fe3e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42fe3e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(42374510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1823969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  911): Prepared write state in 37ms
,I/ProcessStatsService(  911): Pruning old procstats: /data/system/procstats/state-2016-01-14-16-23-00.bin
,I/ProcessStatsService(  911): Prepared write state in 52ms
,D/PMS     (  911): releaseWL(42374510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4304d368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4304d368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42d19ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42a0ff20: PendingIntentRecord{42538030 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1883969, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42d19ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4926): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4926): ====startRecUseTime====
D/htc.customization.log.level( 4926):  is 
W/CustomizationLogLevel( 4926): Level value is invalid, use default level 2
D/CustomizationManager( 4926):  Read ACC file spent 0.111 (s)
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4926): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4926): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4926): Parsing tag category name = system
I/CustomizationCIDLoader( 4926): Parsing tag category name = application
I/CustomizationCIDLoader( 4926): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4926): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4926): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4926): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4926): Parsing tag category name = Settings
D/CustomizationManager( 4926):  Read CID file spent 0.163 (s)
D/CustomizationManager( 4926):  All configurations done spent 0.163 (s)
W/HtcNativeFlag( 4926): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4926): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4926): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4926): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4926, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  911): killProcessQuiet, pid=4521
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  911): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  911): killProcessQuiet, pid=4638
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  911): Killing 4521:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  911): Killing 4638:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/Process (  911): killProcessQuiet, pid=4624
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  911): killProcessQuiet, pid=4608
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  911): killProcessQuiet, pid=3938
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  911): Killing 4624:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  911): Killing 4608:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
I/ActivityManager(  911): Killing 3938:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
I/ActivityManager(  911):   Force finishing activity ActivityRecord{43dc3098 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  911): Recipient 4624
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4608
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3938
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  911): Copying FileAsset 0x63104968 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/MediaRouterService(  911): Client com.google.android.music (pid 3938): Died!
I/ActivityManager(  911): Recipient 4638
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1204): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  911): Got RemoteException sending setActive(false) notification to pid 4521 uid 10389
W/PackageSettings(  911): Skipping PackageSetting{42924868 com.example.hello/10397} due to missing metadata
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  911): WIN DEATH: Window{43b447b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  911): Client connection lost with reason: 4
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1547): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1547): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1547): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 1291): Cleaning up data for package: com.test.thalitest
D/PMS     (  911): acquireWL(438d57f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
W/SQLiteConnectionPool( 2181): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/PMS     (  911): releaseWL(438d57f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/Launcher( 1264): Deferring update until onResume
D/Launcher( 1264): waitUntilResume // bindAppsRemoved
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
W/SystemReader( 1248): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
D/Prism.PackageStateRece_( 1264): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1337): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/[PluginManager]RegisterService( 1337): handle notify Blinkfeed plugin client changed
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/IcingCorporaProvider( 2873): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ExternalAccountType( 1321): Unsupported attribute readOnly
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4941 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
D/PhoneApp( 1233): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/Parcel  ( 1248): Reading a NULL string not supported here.
D/PMS     (  911): acquireWL(444631c8): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2873): UpdateCorporaTask done [took 771 ms] updated apps [took 771 ms] 
E/SQLiteDatabase( 4941): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4941): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4941): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4941): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4941): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4941): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4941): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4941): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4941): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4941): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4941): threadid=11: thread exiting with uncaught exception (group=0x41e1ae30)
E/AndroidRuntime( 4941): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4941): Process: com.google.android.apps.docs, PID: 4941
E/AndroidRuntime( 4941): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4941): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4941): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4941): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4941): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4941): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4941): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4941): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4941): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4959 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4941): killProcess, pid=4941
D/Process ( 4941): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
I/ActivityManager(  911): Recipient 4941
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4941) has died.
W/ContextImpl( 4959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4973 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4959): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4959): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4959): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4959): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4959): threadid=10: thread exiting with uncaught exception (group=0x41e1ae30)
E/AndroidRuntime( 4959): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4959): Process: com.android.keychain, PID: 4959
E/AndroidRuntime( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4959): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4959): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4959): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  911): App crashed! Process: com.android.keychain
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4973): getInstance(Context context)
I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1264): loadItems() com.htc.launcher.pageview.WidgetManager@422ddc68 +
I/Prism.WidgetManager( 1264): onLoadItems() +
D/Process ( 4959): killProcess, pid=4959
D/Process ( 4959): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4973): getInstance(Context context)
D/AppTag  ( 4973): onCreate()
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452862230078.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  911): Recipient 4959
I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  911): Process com.android.keychain (pid 4959) has died.
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  911): acquireWL(42b91020): PARTIAL_WAKE_LOCK  AsyncService 0x1 4094 10160 null
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): releaseWL(42b91020): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4118): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2181): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2181): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2181): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2181): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2181): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2181): Module APK com.google.android.play.games already loaded
I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2181): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2181): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2181): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2181): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e767748
E/SQLiteDBG( 2181): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65a15d50
W/dalvikvm( 2181): threadid=46: thread exiting with uncaught exception (group=0x41e1ae30)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2181): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2181): Process: com.google.android.gms, PID: 2181
E/AndroidRuntime( 2181): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2181): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2181): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2181): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2181): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2181): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2181): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2181): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2181): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2181): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2181): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2181): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2181): 	at java.lang.Thread.run(Thread.java:864)
E/DriveAsyncService( 2181): disk I/O error (code 3850)
E/DriveAsyncService( 2181): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2181): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2181): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2181): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2181): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2181): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2181): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2181): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2181): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2181): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 2181): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2181): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2181): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2181): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2181): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2181): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2181): killProcess, pid=2181
E/SQLiteOpenHelper( 2181): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2181): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2181): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2181): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2181): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2181): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2181): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2181): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2181): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2181): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2181): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  911): handleWLDeath(444631c8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  911): Client connection lost with reason: 4
I/ActivityManager(  911): Recipient 2181
I/ActivityManager(  911): Process com.google.android.gms (pid 2181) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20997ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20995ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20992ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20992ms
I/ActivityManager(  911): Resuming delayed broadcast
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20988ms
E/SQLiteLog( 1354): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1354): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f96160
W/dalvikvm( 1354): threadid=1: thread exiting with uncaught exception (group=0x41e1ae30)
E/AndroidRuntime( 1354): FATAL EXCEPTION: main
E/AndroidRuntime( 1354): Process: com.google.process.gapps, PID: 1354
E/AndroidRuntime( 1354): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1354): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1354): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1354): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1354): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1354): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1354): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1354): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1354): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1354): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1354): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1354): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1354): 	... 10 more
E/ActivityManager(  911): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  911): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5002 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1354): killProcess, pid=1354
D/Process ( 1354): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 5002): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5002 dbg=false s=true
I/DeviceManagement( 5002): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5002): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/ActivityManager(  911): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
W/PackageManager(  911): Unable to load service info ResolveInfo{42d0d478 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/DeviceManagement( 5002): WorkflowService: Starting workflow service
I/DeviceManagement( 5002): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@4227cd50] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5002): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5002): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5002): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5002): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  911): Recipient 1354
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  911): Client connection lost with reason: 4
I/ActivityManager(  911): Process com.google.process.gapps (pid 1354) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30744ms
I/DeviceManagement( 5002): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5002): SessionStateController: Checking invariants...

```
