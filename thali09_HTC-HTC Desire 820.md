#### Test 5065027881383b1_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
,D/CustomizationManager( 4391): ====startRecUseTime====
D/htc.customization.log.level( 4391):  is 
W/CustomizationLogLevel( 4391): Level value is invalid, use default level 2
D/CustomizationManager( 4391):  Read ACC file spent 0.072 (s)
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4391): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4391): Parsing tag category name = system
I/CustomizationCIDLoader( 4391): Parsing tag category name = application
I/CustomizationCIDLoader( 4391): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4391): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4391): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4391): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4391): Parsing tag category name = Settings
D/CustomizationManager( 4391):  Read CID file spent 0.117 (s)
D/CustomizationManager( 4391):  All configurations done spent 0.117 (s)
W/HtcNativeFlag( 4391): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4391): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4391): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4391): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4391
D/PMS     (  910): acquireHCC(42dd3eb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(4369c3e8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1118724936
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@422d90b8
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
D/PMS     (  910): acquireWL(4423bc88): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
E/cutils-trace( 4391): Error opening trace file: No such file or directory (2)
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4402 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1267): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4402): Binding Chromium to main looper Looper (main, tid 1) {421832e0}
I/LibraryLoader( 4402): Expected native library version number "",actual native library version number ""
I/chromium( 4402): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4402): Initializing chromium process, renderers=0
D/PMS     (  910): acquireWL(448ba5c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): acquireWL(44809a18): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): releaseWL(448ba5c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4435e820:true
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4402): 1108970776: getState(). Returning 12
,I/Adreno-EGL( 4402): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4402): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4402): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4402): Local Branch: 
I/Adreno-EGL( 4402): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4402): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4402):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4402): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4402): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4402): CordovaWebView is running on device made by: HTC
,W/AwContents( 4402): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  910): Disable input method client, pid=1267
,W/ResourceType( 4402): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4402): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@421ca3c8, mServedView=org.apache.cordova.engine.SystemWebView{42190030 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  910): Enable input method client, pid=4402
,W/AwContents( 4402): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +397ms
,D/PMS     (  910): releaseWL(4423bc88): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/SensorManager(  910): mEventCount = 900
,D/JsMessageQueue( 4402): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4402): JniHelper::setJavaVM(0x41d38010), pthread_self() = 1662663288
,D/JX-Cordova( 4402): jxcore cordova android initializing
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.520MB for 64402-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.640MB for 144892-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.755MB for 217334-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.931MB for 325996-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 12.206MB for 488990-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 12.611MB for 733480-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 14.058MB for 1650320-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 15.472MB for 2475476-byte allocation
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 17.498MB for 3713210-byte allocation
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
D/PMS     (  910): releaseHCC(42dd3eb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(4369c3e8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4402): Initializing JXcore engine
,W/jxcore-log( 4402): JXcore engine is ready
,W/jxcore-log( 4402): Starting JXcore engine
,W/jxcore-log( 4402): Platform android
W/jxcore-log( 4402): 
,W/jxcore-log( 4402): Process ARCH arm
W/jxcore-log( 4402): 
,I/jxcore-log( 4402): JXcore Cordova bridge is ready!
I/jxcore-log( 4402): 
,W/jxcore-log( 4402): JXcore engine is started
,I/chromium( 4402): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  910): releaseWL(44809a18): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4402): Toggling radios to true
I/jxcore-log( 4402): 
,D/BluetoothAdapter( 4402): enable(): BT is already enabled..!
,D/WifiManager( 4402): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
D/WifiService(  910): New client listening to asynchronous messages
D/WifiService(  910): setWifiEnabled: true pid=4402, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 920
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
W/Settings:Agent(  910): << traceCallingStack(): 0(ms)
D/WifiManager( 4402): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
D/WifiManager( 4402): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): TDLS: Tear down peers
I/wpa_supplicant( 1180): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4402): Radios toggled
I/jxcore-log( 4402): 
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4402): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4402): 
I/jxcore-log( 4402): Perf Test app loaded loaded
I/jxcore-log( 4402): 
I/jxcore-log( 4402): check test folder
I/jxcore-log( 4402): 
I/jxcore-log( 4402): found test : ./testFindPeers.js
I/jxcore-log( 4402): 
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 48
,I/wpa_supplicant( 1180): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1180): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): TDLS: Remove peers on disassociation
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb860dbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1180): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1180): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  910):    returned true
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910):    returned true
I/jxcore-log( 4402): found test : ./testSendData.js
I/jxcore-log( 4402): 
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  910):    returned true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(435f5308): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: RECONNECT
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): Fast associate: Old scan results
I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1180): nl80211: Event message available
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20129 mDataStallAlarmIntent=PendingIntent{43383c18: PendingIntentRecord{42b0f2c8 android broadcastIntent}}
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WISPrService( 3770): >>>>>WISPrService start isConnected = false<<<<<
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3770): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  910): New client listening to asynchronous messages
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
,D/ConnectivityService(  910): resetConnections(wlan0, 3)
,V/NativeCrypto( 1367): Read error: ssl=0x64689dc8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x64689dc8: I/O error during system call, Broken pipe
D/PMS     (  910): acquireWL(42cd2008): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  910): acquireWL(42cbb1b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  363): [NET] entry_id:7   entry:0xb879ce80  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb879cdb8  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb879cc88  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb879cf70  removed 
D/WISPrService( 3770): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] entry_id:5   entry:0xb8793c20  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8798458  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb87982d8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3770): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1367/10029)
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  910): acquireWL(42caf3e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/PMS     (  910): releaseWL(42cd2008): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  910): doBoolean: SCAN
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  910):    returned false
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/BatSI   (  910): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  910): releaseWL(42caf3e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/PMS     (  910): acquireWL(42c4a918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@427d4908
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@427d4908, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4221a5a0
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@42d33850
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  910): Going to sleep due to screen timeout...
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
,I/Choreographer( 4402): Skipped 87 frames!  The application may be doing too much work on its main thread.
,W/PMS     (  910): mWirelessDisplayManager is null
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/VacuumService( 1222): Vacuum at: now=1449752916850 tag=VacuumService
,I/chromium( 4402): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PMS     (  910): acquireWL(42ba0f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42cbb1b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  910): releaseWL(42ba0f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43c7d0f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42c4a918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/PMS     (  910): releaseWL(43c7d0f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43878a50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/PMS     (  910): releaseWL(43878a50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43396960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
,D/PMS     (  910): releaseWL(43396960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 340ms
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
,I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
,D/HABCtrl (  910): TPE algorithm. remove timeout.
,D/PMS     (  910): OOBE c monitor 11
,I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1254): ScreenObserver: OFF
D/NfcService( 1254): applyRouting - 0
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43d11988)
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
,D/NfcService( 1254): applyRouting -2
D/PMN     (  910): wakingUp
D/PMS     (  910): acquireWL(43d117b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): acquireWL(446ede98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/InputMethodManagerService(  910): Disable input method client, pid=4402
I/WindowManager(  910): No lock screen! windowToken=null
D/PMS     (  910): releaseWL(446ede98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  910): releaseWL(43d117b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/ResourceType( 4402): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4402): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42190030 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMN     (  910): onScreenOn
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/NfcService( 1254): applyRouting - 0
,D/MtpService( 2709): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2709): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting -2
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): acquireWL(43698ad8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,D/PMS     (  910): releaseWL(43698ad8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AutoSetting( 1341): receiver - intent: android.intent.action.USER_PRESENT
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
D/TetherSettings( 3770): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3770): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3770): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3770): Cust_ConnectToPC   : spcsc>false
D/        ( 3770): Cust_ConnectToPC   : IPT>true
D/        ( 3770): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3770): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3770): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3770): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3770): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
D/AutoSetting( 1341): service - onCreate()
D/AutoSetting( 1341): service - AddressCache: using context: com.htc.Weather
,I/PSReceiver( 3770): onReceive:android.intent.action.USER_PRESENT
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:On
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/ClockThread( 1118): stop update clock
,I/SmartNS_PSService( 3770): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3770): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  910):    returned true
,I/SmartNS_PSService( 3770):  defaultType:0
W/ContextImpl( 3770): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/LocationManagerService(  910): request 42af0230 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/AutoSetting( 1341): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  910): updateScreenOn: false
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4465 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): acquireWL(43c04af8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43c04af8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43be67a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1736): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1736): onScreenOn: 1449752917514
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1736): onScreenOn: 1449752917514
D/PMS     (  910): releaseWL(43be67a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4221a5a0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4221a5a0, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@42d33850
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
W/ContextImpl( 4465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  910): acquireWL(42c039b0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/PMS     (  910): releaseWL(42c039b0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20130 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  910): doBoolean: SET pno 1
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:Off
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1180): get_ip_address source addr = 02000000
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='1'
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
D/PMS     (  910): acquireWL(4472b7e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
,D/PMS     (  910): acquireWL(438d4850): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4465 1000 null
D/SmartSyncUtils( 4465): isEpsOn(), nState = 0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  910): updateScreenOn: false
,D/ContactMessageStore( 1236): start background delete task...
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1180): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
D/wpa_supplicant( 1180): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/ContactMessageStore( 1236): size: 0 , 0
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
D/ContactMessageStore( 1236): Background delete complete
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 3
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 1
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): selected network = 1
D/wpa_supplicant( 1180): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb860f4e8  current_ssid=0x0
D/wpa_supplicant( 1180): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1180): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1180): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1180): check if in concurrent case
D/WifiNative-wlan0(  910):    returned true
,I/wpa_supplicant( 1180): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1180): RSN: PMKSA cache search - network_ctx=0xb860f4e8 try_opportunistic=0
D/wpa_supplicant( 1180): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1180): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1180): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1180): nl80211: Unsubscribe mgmt frames handle 0xb860e718 (mode change)
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1180): nl80211: Subscribe to mgmt frames with non-AP handle 0xb860e718
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb860e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1180):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180):   * freq=2412
D/wpa_supplicant( 1180):   * Auth Type 0
D/wpa_supplicant( 1180):   * WPA Versions 0x2
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1180): nl80211: Connect request send successfully
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-50
I/wpa_supplicant( 1180): tsf=0000000022239895
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-51
I/wpa_supplicant( 1180): tsf=0000000104598211
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=2
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2427
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000000022239911
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/PMS     (  910): releaseWL(4472b7e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 22239895, distance: ?(cm), distanceSd: ?(cm)
D/PMS     (  910): releaseWL(438d4850): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/SmartSyncUtils( 4465): getMobilePolicyEnabled, result = true
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 104598211, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 22239911, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4465): isEpsOn(), nState = 0
D/SmartSyncUtils( 4465): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4465): isEpsOn(), nState = 0
D/WifiService(  910): New client listening to asynchronous messages
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42d33850
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42d33850, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42d33850, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42d33850
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42d33d98 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42d33d98 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1557): [EventService] getTotalRam: 1873 Mb
D/PMS     (  910): acquireWL(43fca360): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43fca360): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42cd6360): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1736): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1736): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1736): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1736): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1736): onScreenOff
D/PMS     (  910): releaseWL(42cd6360): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1341): service - mHandler: cancel location update
,D/AutoSetting( 1341): service -           changes count: 0
,D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Connect event
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1180): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Add randomness: count=7 entropy=1
I/wpa_supplicant( 1180): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): TDLS: Remove peers on association
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1180): EAPOL: enable timer tick
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  910): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1180): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1180): Get randomness: len=32 entropy=2
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d,3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  910): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb860e9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f7cb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1180):    broadcast key
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1180): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1180): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1180): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1180): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1180): set send_ind_to_ndc = 0
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (1)+
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1180): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1180): EAPOL authentication completed successfully
I/wpa_supplicant( 1180): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
V/Tethering(  910): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): DISCONNECTED
I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4488 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(44768b58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(44768b58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1567/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4253/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4253/10100)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WISPrService( 3770): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3770): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1180): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 1
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1180): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(43e14b38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42c81288 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42c81288 target=com.android.internal.util.StateMachine$SmHandler }
,I/MusicStore( 4488): Database version: 95
,W/ContextImpl( 4488): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4488): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4488, uid=10154, userID:0
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/MediaRouterService(  910): Client com.google.android.music (pid 4488): Registered
,I/MediaRouter( 4488): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4488/10154)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2709/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4512 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4488): getSelectedRoute
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4488/10154)
,I/NetworkMonitor( 4488): type=WIFI subType= reason=null isConnected=false
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4488, uid=10154, userID:0
,D/ACRA    ( 4512): ACRA is enabled for com.facebook.katana, intializing...
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43f7d218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/Process (  910): killProcessQuiet, pid=4186
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4512): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4512): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  910): Killing 4186:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/PMS     (  910): releaseWL(43f7d218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  910): Recipient 4186
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4512): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4512): Preparing secondary program dexes.
V/DexLibLoader( 4512): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4512): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4512): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4512): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4512): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4512): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4512): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4512): Dex already copied
D/OdexVerifier( 4512): Odex verification is skipped.
,V/DexLibLoader( 4512): Creating class loader
,V/DexLibLoader( 4512): Finished creating class loader
V/DexLibLoader( 4512): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4512): Dex already copied
D/OdexVerifier( 4512): Odex verification is skipped.
,V/DexLibLoader( 4512): Creating class loader
,V/DexLibLoader( 4512): Finished creating class loader
V/DexLibLoader( 4512): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4512): Dex already copied
D/OdexVerifier( 4512): Odex verification is skipped.
,V/DexLibLoader( 4512): Creating class loader
,V/DexLibLoader( 4512): Finished creating class loader
V/DexLibLoader( 4512): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4512): Dex already copied
D/OdexVerifier( 4512): Odex verification is skipped.
,V/DexLibLoader( 4512): Creating class loader
,V/DexLibLoader( 4512): Finished creating class loader
,V/DexLibLoader( 4512): Verifying classes from secondary dexes.
,D/DexLibLoader( 4512): DexLibLoader.ensureDexLoaded took 19 ms
,D/wpa_supplicant( 1180): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1180): EAPOL: disable timer tick
,W/dalvikvm( 4512): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4512): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4512): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4512): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4512): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4512): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4512): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4512): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4512): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4512): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4512): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4512): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4512): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 9.517MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=3813
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 3813:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/AutoSetting( 1341): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1341/10055)
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4557 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1341): Util - no network available!
,D/AutoSetting( 1341): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1341): service - mHandler: cancel location update
,D/AutoSetting( 1341): service -           changes count: 0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1341/10055)
,W/fb4a(:<default>):UserScope( 4512): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4512): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4557): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4557): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4557): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4557): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4512): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4571 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=4017
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 4017:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10079)
I/ActivityManager(  910): Recipient 3813
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10079)
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4585 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
,D/Process (  910): killProcessQuiet, pid=4221
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 4221:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  910): releaseWL(43e14b38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/ActivityManager(  910): Recipient 4221
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  910): WAN detection
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 9.960MB for 84664-byte allocation
,D/WISPrService( 3770): >>>>>WISPrService start isConnected = true<<<<<
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42afbaa8
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
I/ActivityManager(  910): Recipient 4017
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  910): Failed to clear dns cache for: com.google.android.talk
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  910): acquireWL(43d6d118): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10079)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/dalvikvm-heap( 4512): Grow heap (frag case) to 9.975MB for 28144-byte allocation
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
E/dalvikvm( 4512): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4512): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4512): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4512): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4512): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4512): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/dalvikvm( 4512): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4512): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4512): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4512): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4512): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4512): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/ContextImpl( 4585): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/dalvikvm( 4512): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4512): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4512): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4512): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4512): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4512): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/PMS     (  910): releaseWL(43d6d118): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4585): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
D/PMS     (  910): acquireWL(43a84710): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1449752869291 min interval config: 0 actual interval: 50512
D/PMS     (  910): acquireWL(43ab7110): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43a84710): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2183): Checking schedule, now: 1449752919808 next: 1449752899263
,I/CheckinService( 2183): active receiver: enabled
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2183, uid=10029, userID:0
I/dalvikvm-heap( 4512): Grow heap (frag case) to 10.024MB for 39954-byte allocation
,W/GAV2    ( 4585): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 10.100MB for 79892-byte allocation
,I/CheckinService( 2183): Preparing to send checkin request
,I/EventLogService( 2183): Accumulating logs since 1449752865022
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4585): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4585): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 10.283MB for 75760-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4341caf0 u0 ReceiverList{42dfb430 4512 com.facebook.katana/10027/u0 remote:42ac0ca8}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4341caf0 u0 ReceiverList{42dfb430 4512 com.facebook.katana/10027/u0 remote:42ac0ca8}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{433eecf8 u0 ReceiverList{42ddbd20 4512 com.facebook.katana/10027/u0 remote:42aa2a98}}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4585/10151)
,V/WebViewChromiumFactoryProvider( 4585): Binding Chromium to main looper Looper (main, tid 1) {4217e360}
,I/LibraryLoader( 4585): Expected native library version number "",actual native library version number ""
,I/chromium( 4585): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4585): Initializing chromium process, renderers=0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,E/AudioManagerAndroid( 4585): BLUETOOTH permission is missing!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
D/PMS     (  910): acquireWL(44717678): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): acquireWL(44717538): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): releaseWL(44717678): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4585): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4585): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4585): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4585): Local Branch: 
I/Adreno-EGL( 4585): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4585): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4585):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/PMS     (  910): acquireWL(44704db8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
I/NSApplication( 4585): Starting up...
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(44704db8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4585/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4585/10151)
V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4058/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4058/10160)
,D/Process (  910): killProcessQuiet, pid=4253
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4253:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4636 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4636): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4636): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4636): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4636): install
,I/MultiDex( 4636): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4636): loading existing secondary dex files
,I/MultiDex( 4636): load found 3 secondary dex files
,I/MultiDex( 4636): install done
I/ActivityManager(  910): Recipient 4253
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4636): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4636): VFY: unable to resolve instance field 36
,W/dalvikvm( 4636): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4636): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4636): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4636): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4636): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,W/dalvikvm( 4636): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4636): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4636): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4636): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4636): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2183): Restart initialization of location
,E/MDM     ( 1222): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  910): acquireWL(4436c100): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4436c100): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4636): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=3589013968
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
D/PMS     (  910): releaseWL(435f5308): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1567/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3868/10053)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(42c98bc8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4557/10079)
D/PMS     (  910): acquireWL(42c78268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 4488): type=WIFI subType= reason=null isConnected=true
D/WVCdm   (  370): PrepareKeyRequest: nonce=1856859118
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4488/10154)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/PMS     (  910): releaseWL(42c78268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(42c98bc8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1567/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(42c72ae8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2709/10021)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(42c72ae8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  370): CdmEngine::CloseSession
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/Settings( 4636): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1341): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4557): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4557): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1341): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1341): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1341/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1341/10055)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4585/10151)
D/AutoSetting( 1341): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1341): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4058/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4058/10160)
D/PMS     (  910): acquireWL(43cbb7a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1449752869291 min interval config: 0 actual interval: 51624
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43cbb7a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4058): Grow heap (frag case) to 13.509MB for 1821008-byte allocation
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,I/Adreno-EGL( 4636): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4636): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4636): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4636): Local Branch: 
I/Adreno-EGL( 4636): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4636): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4636):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4636): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4636): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4636): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4636): Local Branch: 
I/Adreno-EGL( 4636): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4636): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4636):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4636/10029)
,I/Adreno-EGL( 4636): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4636): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4636): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4636): Local Branch: 
I/Adreno-EGL( 4636): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4636): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4636):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2183): [NET] getaddrinfo-, 1
,D/libc    ( 2183): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =85f1 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2183): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,I/jxcore-log( 4402): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4402): 
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2183): Sending checkin request (12126 bytes)
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=19 [21][4][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,I/CheckinTask( 2183): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2183): Checking schedule, now: 1449752922501 next: 1450275859497
,I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
I/CheckinService( 2183): Checking schedule, now: 1449752922529 next: 1450275859497
,I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/CheckinService( 2183): Recording last checkin time for package unspecified as 1449752922536
,D/PMS     (  910): releaseWL(43ab7110): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/PMS     (  910): acquireWL(43e02de8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2e49 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 274
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/PMS     (  910): acquireWL(43d5ce48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d8ea +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  910): acquireWL(44774f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44004830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,D/PMS     (  910): releaseWL(44004830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43d5ce48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(425622e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
,D/PMS     (  910): acquireWL(43a92270): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(425622e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  910): releaseWL(43e02de8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44774f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): acquireWL(43aa4128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/PMS     (  910): releaseWL(43aa4128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43a92270): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43bd9998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43d3e648): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
D/PMS     (  910): releaseWL(43d3e648): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43bd9998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44717538): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  910): acquireWL(42c64740): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4488 10154 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,W/ContextImpl( 4488): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4488, uid=10154, userID:0
,I/MusicLeanback( 4488): Conditions not met for autocaching.
,I/MusicLeanback( 4488): Stop autocaching.
D/PMS     (  910): releaseWL(42c64740): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4488): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/fb4a(:<default>):UserScope( 4512): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4512): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4512): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4512/10027)
,I/GAV2    ( 4585): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1513): service - handleMessage() stop self
,D/AutoSetting( 1513): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=4269
,D/AutoSetting( 1513): service - handleMessage() quit looper
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4269:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4269
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  910): killProcessQuiet, pid=4293
,I/ActivityManager(  910): Killing 4293:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4293
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4697 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1267): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/Launcher( 1267): Deferring update until onResume
,D/Launcher( 1267): waitUntilResume // bindAppsUpdated
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4697): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4697): MmsConfig.loadMmsSettings
,W/dalvikvm( 4697): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4697): VFY: unable to resolve instance field 36
,W/dalvikvm( 4697): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4697): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4697, uid=10111, userID:0
,W/Settings( 4697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4720 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4697, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4697, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4697, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4697, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4697, uid=10111, userID:0
,D/PMS     (  910): acquireWL(44210160): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4697 10111 null
,D/MessageFrequencyProvider( 4720): onCreate
I/[PluginManager]RegisterService( 1341): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1341): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,W/PackageManager(  910): Unable to load service info ResolveInfo{42cd3800 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  910): Resuming delayed broadcast
,I/ProviderInstaller( 4697): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  910): releaseWL(44210160): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
V/GetPrviateResource( 4720): GetPrviateResource
D/MmsCustomizationProvider( 4720): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 4720): GetPrviateResource
I/IcingCorporaProvider( 2808): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/Process (  910): killProcessQuiet, pid=4240
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  910): killProcessQuiet, pid=3868
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4240:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  910): Killing 3868:com.htc.musicenhancer/u0a53 (adj 15): empty #18
,I/ActivityManager(  910): Recipient 4240
,I/ActivityManager(  910): Recipient 3868
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(44729830): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44729830): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(447176c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4058 10160 null
,D/MmsCustomizationProvider( 4720): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/PMS     (  910): acquireWL(44717678): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/Babel   ( 4697): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4697): MmsConfig.loadFromDatabase
,I/dalvikvm-heap( 4058): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
,E/Babel   ( 4697): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4697): MmsConfig.loadFromResources
D/MessageCustFlag( 4720): sense_version=6.0
,D/BTAccessoryUtil( 4720): createReceiver
,D/BTAccessoryUtil( 4720): registerReceiver return intent = null
E/Babel   ( 4697): canonicalizeMccMnc: invalid mccmnc nullnull
D/MessageCustFlag( 4720): sku_id=99
,D/PMS     (  910): releaseWL(447176c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/SystemReader( 4720): Cannot find message_ambs_application_id, use default value instead
I/Babel   ( 4697): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/Messaging( 4720): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4720): networkCode: 
,D/MessageCustFlag( 4720): sku_id=99
D/MmsConfig( 4720): SIE smsPri: null
,D/MmsConfig( 4720): networkCode: 
,I/dalvikvm-heap( 4058): Grow heap (frag case) to 16.945MB for 1821008-byte allocation
,D/HtcTelephonyCapability( 4720): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4720): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4720): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4720): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  910): releaseWL(44717678): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(4430e370): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  910): releaseWL(4430e370): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  910): acquireWL(4400d7d0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4400d7d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  910): acquireWL(43feaa80): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43feaa80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43fc4310): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 2183): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2183): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(42985870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): releaseWL(42985870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42286c70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42286c70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4342a228): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/PMS     (  910): releaseWL(4342a228): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PMS     (  910): acquireWL(42cb8070): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42cb8070): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2808): UpdateCorporaTask done [took 553 ms] updated apps [took 553 ms] 
I/ActivityManager(  910): Resuming delayed broadcast
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1267): loadItems() com.htc.launcher.pageview.WidgetManager@4220ec70 +
,I/Prism.WidgetManager( 1267): onLoadItems() +
,E/Prism.WidgetManager( 1267): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1267): onLoadItems() -
,I/Prism.ItemManager( 1267): loadItems() com.htc.launcher.pageview.WidgetManager@4220ec70 -
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(43fc4310): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1236): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1236): -- N1 =0
,D/PhoneApp( 1236): -- N2 =0
,D/PhoneApp( 1236): -- N3 =0
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{441f29a8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/Messaging( 4720): mNeedToUpdateDate2 start
,D/MmsConfig( 4720): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4720): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4720): 
D/MmsAsyncWorkHandler( 4720): HM tk = 20001
,D/ReportIndicatorCache( 4720): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4720): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@4218a510
,I/Messaging( 4720): mccmnc> 
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1236):  phoneType = -1
D/DraftCache( 4720): [DraftCache/1] DraftCache.constructor
D/DraftCache( 4720): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4720): networkCode: 
,D/Messaging( 4720): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1236): sku_id=99
D/MessageCustFlag( 4720): sense_version=6.0
D/PhoneStorageUtil( 4720): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4720): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4720): createReceiver
,D/Jerry   ( 4720): start to preload cursor >>>>>>>
,D/TelephUtils( 1236): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/DraftCache( 4720): [DraftCache/469] rebuildCache
,V/MmsProvider( 1236): Update uri=content://mms, match=0
V/MmsProvider( 1236): selection=st=129 AND m_type!=134
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4720): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4720): TransactionService is going to be woken up.
,D/Messaging( 4720): mNeedToUpdateDate2: false
,V/TransactionService( 4720): 1-Creating TransactionService
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
V/TransactionService( 4720): onStartCommand: 1
,D/MmsSystemEventReceiver( 4720): unRegisterForConnectionStateChanges
V/TransactionService( 4720): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4720): Loading previous transactions.
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1236): device_type: 1
D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/Jerry   ( 1236): URI_DRAFT
,D/Messaging( 4720): ViewCache CreatePreload
,D/Messaging( 4720): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TransactionService( 4720): Force set service start id to 1
,V/TransactionService( 4720): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4720): unRegisterForConnectionStateChanges
D/Cust_MMSMS( 4720): _has_set_default_values_2=true
D/TransactionService( 4720): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4720): Destroying TransactionService
D/DraftCache( 4720): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4720): [DraftCache/469] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4720): 
D/MmsAsyncWorkHandler( 4720): HM tk = 20002
,V/TransactionService( 4720): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/MsgPreferenceUtils( 4720): def_index: 0
D/Messaging( 4720): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 4720): globalIndex = 1
D/MsgPreferenceUtils( 4720): phone state: true
D/MsgPreferenceUtils( 4720): sd state: false
,D/MsgPreferenceUtils( 4720): vIndex = 0
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1236): sku_id=99
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1236): sku_id=99
,I/GAV4    ( 4697): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(43879378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4238e240: PendingIntentRecord{42172e20 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=127025, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43879378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42cedca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(42cedca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus,
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43bc4b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{433da450: PendingIntentRecord{42cce7b8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134704, Int=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  910): releaseWL(43bc4b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42c06240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=20 [15][3][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
,D/PMS     (  910): acquireWL(429eb1d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42c06240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 8424 seconds from now (1449752948126)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2f3d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 285
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=50 [8][4][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(429eb1d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(446dbc98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
,D/PMS     (  910): releaseWL(446dbc98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42d11528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024233
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024400
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024470
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024476
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024480
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025849
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029472
,D/PMS     (  910): releaseWL(42d11528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1341): service - has update message, not stop
,D/AutoSetting( 1341): service - mHandler: update timezone
,D/AutoSetting( 1513): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1513): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1513): service - onCreate()
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1513): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1513): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1557): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1513): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1513): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1513): service - mHandler: update timezone
,D/AutoSetting( 1513): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1513): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1513): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1513): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{421d93e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 1 8 2 11
,D/PMS     (  910): acquireWL(43ab1400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4240e250: PendingIntentRecord{426ae0e0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141574, Int=0
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  910): acquireWL(42b5fa28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(43ab1400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =aacd +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(42b5fa28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44373180 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(447081f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(447081f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1341): service - handleMessage() stop self
,D/AutoSetting( 1341): service - handleMessage() quit looper
,D/AutoSetting( 1341): service - onDestroy() END
,I/ActivityManager(  910): Killing 4324:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4324
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4324
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AutoSetting( 1513): service - handleMessage() stop self
,D/AutoSetting( 1513): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=4339
,I/ActivityManager(  910): Killing 4339:com.android.settings:remote/1000 (adj 15): empty #17
D/AutoSetting( 1513): service - handleMessage() quit looper
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4339
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(446d9850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{43efba08: PendingIntentRecord{442a5428 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172498, Int=0
,D/PMS     (  910): releaseWL(446d9850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1236): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(4476f850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4238e240: PendingIntentRecord{42172e20 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=187025, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4476f850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43df4610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43df4610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4400ea00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(4400ea00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43de1228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4238e240: PendingIntentRecord{42172e20 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=247026, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43de1228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42d60b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
D/HtcPowerSaver(  910): updateBatteryInfo
,D/PMS     (  910): releaseWL(42d60b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(44005620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44005620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(433c8a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4238e240: PendingIntentRecord{42172e20 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=307025, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(433c8a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(440022b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440022b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1

```
