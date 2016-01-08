#### Test 5497026140aeaf4_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,--------- beginning of /dev/log/system
I/ActivityManager(  906): Waited long enough for: ServiceRecord{44613bf0 u0 com.htc.htclocationservice/.AutoSettingService}
E/cutils-trace( 4362): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4362): ====startRecUseTime====
D/htc.customization.log.level( 4362):  is 
W/CustomizationLogLevel( 4362): Level value is invalid, use default level 2
D/CustomizationManager( 4362):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4362): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4362): Parsing tag category name = system
I/CustomizationCIDLoader( 4362): Parsing tag category name = application
I/CustomizationCIDLoader( 4362): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4362): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4362): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4362): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4362): Parsing tag category name = Settings
D/CustomizationManager( 4362):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4362):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 4362): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4362): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4362): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4362): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4362
D/PMS     (  906): acquireHCC(42591608): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(424cb3a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6f170f90 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1113281104
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42009a60
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
D/PMS     (  906): acquireWL(423bd758): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/SensorManager(  906): mEventCount = 1200
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4373 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4373): Copying FileAsset 0x5c827428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4373): Binding Chromium to main looper Looper (main, tid 1) {41ae9a10}
I/LibraryLoader( 4373): Expected native library version number "",actual native library version number ""
I/chromium( 4373): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4373): Initializing chromium process, renderers=0
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41e5c128:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  906): acquireWL(42112170): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): acquireWL(41fc5df8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(41fc5df8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4373): 1102069728: getState(). Returning 12
I/Adreno-EGL( 4373): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4373): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4373): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4373): Local Branch: 
I/Adreno-EGL( 4373): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4373): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4373):                  aa63bbd948f41d15fc72f585e
W/chromium( 4373): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4373): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4373): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4373): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4373): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4373): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4373): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4373): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4373): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4373): CordovaWebView is running on device made by: HTC
,W/AwContents( 4373): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1271
,W/ResourceType( 4373): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4373): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b35690, mServedView=org.apache.cordova.engine.SystemWebView{41afb2f8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=4373
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +286ms
,W/AwContents( 4373): nativeOnDraw failed; clearing to background color.
,D/PMS     (  906): releaseWL(423bd758): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4373): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4373): JniHelper::setJavaVM(0x415c5048), pthread_self() = 1662550624
,D/JX-Cordova( 4373): jxcore cordova android initializing
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 11.581MB for 95956-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 11.660MB for 143930-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 11.774MB for 215890-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 11.950MB for 323830-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 12.222MB for 485740-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 13.221MB for 1092904-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 14.094MB for 1639352-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 15.444MB for 2459024-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 17.453MB for 3688532-byte allocation
,W/jxcore-log( 4373): Initializing JXcore engine
,W/jxcore-log( 4373): JXcore engine is ready
,W/jxcore-log( 4373): Starting JXcore engine
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(42591608): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(424cb3a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4373): Platform android
W/jxcore-log( 4373): 
,W/jxcore-log( 4373): Process ARCH arm
W/jxcore-log( 4373): 
,I/jxcore-log( 4373): JXcore Cordova bridge is ready!
I/jxcore-log( 4373): 
,W/jxcore-log( 4373): JXcore engine is started
,I/chromium( 4373): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4373): Toggling radios to true
I/jxcore-log( 4373): 
,D/BluetoothAdapter( 4373): enable(): BT is already enabled..!
,D/WifiManager( 4373): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
D/WifiService(  906): setWifiEnabled: true pid=4373, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1606
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
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
,W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/WifiManager( 4373): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
,D/WifiManager( 4373): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): TDLS: Tear down peers,
,I/wpa_supplicant( 1167): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4373): Radios toggled,
I/jxcore-log( 4373): 
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiService(  906): New client listening to asynchronous messages
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1167): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1167): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1167): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb710bbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1167):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1167): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1167): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operst,ate=5
D/Tethering(  906): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1167): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  906):    returned true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec,
,D/PMS     (  906): acquireWL(423b0a58): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): Fast associate: Old scan results
I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiNative-wlan0(  906):    returned true
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/WifiStateMachine(  906): Enter handleNetworkDisconnect
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19974 mDataStallAlarmIntent=PendingIntent{423853d0: PendingIntentRecord{4245fee8 android broadcastIntent}}
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
D/UsbnetStateTracker(  906): isAvailable+-
,D/WISPrService( 4151): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  906): New client listening to asynchronous messages
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4151): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4151): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4151): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:5   entry:0xb84a7818  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb84a72d8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb84a7108  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb84a6ec0  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb84a71d0  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb84a7410  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb84a6d90  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/PMS     (  906): acquireWL(42388000): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/PMS     (  906): acquireWL(4267a9c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): releaseWL(4267a9c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1367/10028)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/PMS     (  906): releaseWL(42388000): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  906): acquireWL(4247e560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:2
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  906): releaseWL(4247e560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(43feffd8): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
,D/PMS     (  906): releaseWL(43feffd8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42574c60): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
,D/PMS     (  906): releaseWL(42574c60): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42d56050): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
,D/PMS     (  906): releaseWL(42d56050): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4337b7b0): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
,D/PMS     (  906): releaseWL(4337b7b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): releaseWL(42112170): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42e25940): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/NetworkMonitor( 3873): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3873/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1903/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2028/10021)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4429 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): releaseWL(42e25940): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4429): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4429): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4429): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4429): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4429): Preparing secondary program dexes.
V/DexLibLoader( 4429): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4429): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4429): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4429): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4429): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4429): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4429): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4429): Dex already copied
D/OdexVerifier( 4429): Odex verification is skipped.
,V/DexLibLoader( 4429): Creating class loader
,V/DexLibLoader( 4429): Finished creating class loader
V/DexLibLoader( 4429): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4429): Dex already copied
D/OdexVerifier( 4429): Odex verification is skipped.
,V/DexLibLoader( 4429): Creating class loader
,V/DexLibLoader( 4429): Finished creating class loader
V/DexLibLoader( 4429): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4429): Dex already copied
D/OdexVerifier( 4429): Odex verification is skipped.
,V/DexLibLoader( 4429): Creating class loader
V/DexLibLoader( 4429): Finished creating class loader
V/DexLibLoader( 4429): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar,
V/DexLibLoader( 4429): Dex already copied
D/OdexVerifier( 4429): Odex verification is skipped.
,V/DexLibLoader( 4429): Creating class loader,
V/DexLibLoader( 4429): Finished creating class loader
,V/DexLibLoader( 4429): Verifying classes from secondary dexes.
,D/DexLibLoader( 4429): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4429): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4429): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4429): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4429): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4429): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4429): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4429): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4441 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(43436990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{423a70e8: PendingIntentRecord{42093910 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452278316149, Int=60000
,D/PMS     (  906): releaseWL(43436990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4441): SMSBackupAgentService started
,D/SMSBackup( 4441): Checking restore status
,D/SMSBackup( 4441): Restore complete
,D/SMSBackup( 4441): cancelCheckAlarm
,D/SMSBackup( 4441): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3201
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3201:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3201
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1167): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1167): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1167): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1167): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1167): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 3
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 1
I/wpa_supplicant( 1167): wpa_s->is_screen_on 1
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): selected network = 1
D/wpa_supplicant( 1167): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb710d4e8  current_ssid=0x0
D/wpa_supplicant( 1167): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1167): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1167): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1167): check if in concurrent case
I/wpa_supplicant( 1167): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-,wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1167): RSN: PMKSA cache search - network_ctx=0xb710d4e8 try_opportunistic=0
D/wpa_supplicant( 1167): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1167): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1167): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1167): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1167): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1167): nl80211: Unsubscribe mgmt frames handle 0xb710c718 (mode change)
D/wpa_supplicant( 1167): nl80211: Subscribe to mgmt frames with non-AP handle 0xb710c718
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1167):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1167):   * freq=2412
D/wpa_supplicant( 1167):   * Auth Type 0
D/wpa_supplicant( 1167):   * WPA Versions 0x2
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1167): nl80211: Connect request send successfully
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (632) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-47
I/wpa_supplicant( 1167): tsf=0000000104891047
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-53
I/wpa_supplicant( 1167): tsf=0000000104891064
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-78
I/wpa_supplicant( 1167): tsf=0000000104891068
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000104891071
I/wpa_supplicant( 1167): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC Wi-Free
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-53
I/wpa_supplicant( 1167): tsf=0000000104891059
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 104891047, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (5) end of scan result ==
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 104891064, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 104891068, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -82, frequency: 2437, timestamp: 104891071, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 104891059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
W/dalvikvm( 4429): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4429): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1167): nl80211: Connect event
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1167): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1167): Add randomness: count=12 entropy=5
I/wpa_supplicant( 1167): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1167): TDLS: Remove peers on association
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1167): EAPOL: enable timer tick
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1167): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1167): Get randomness: len=32 entropy=6
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=1, interv,al=30
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1167): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb710c9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1167):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1167): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f1bb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1167):    broadcast key
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1167): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1167): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1167): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1167): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1167): set send_ind_to_ndc = 0
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1167): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1167): EAPOL authentication completed successfully
I/wpa_supplicant( 1167): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
,D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
,D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/Tethering(  906): [isWifi] getHotspotEnabled: false,
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4151): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4151): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 1
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(43f8de28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423852b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423852b0 target=com.android.internal.util.StateMachine$SmHandler }
,E/FbInjectorInitializer( 4429): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4429): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4429): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4429): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4202
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4202:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  906): acquireWL(43529298): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2245 10028 null
,D/PMS     (  906): acquireWL(43b5dd48): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2245 10028 null
,D/PMS     (  906): releaseWL(43529298): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
,D/AutoSetting( 1399): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4471 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
,D/AutoSetting( 1399): Util - no network available!
,D/AutoSetting( 1399): service - onCreate()
,D/AutoSetting( 1399): service - AddressCache: using context: com.htc.Weather
,D/PMS     (  906): releaseWL(43b5dd48): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  906): request 425a8038 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1399): service - mHandler: cancel location update
,D/AutoSetting( 1399): service -           changes count: 0
,D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Recipient 4202
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4429): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4429): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4429): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4471): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4471): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4471): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4471): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4487 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4471/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4471/10078)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4429): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4471/10078)
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/dalvikvm( 4429): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4429): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4429): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4429): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4429): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4429): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4429): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4429): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4429): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4429): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4429): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4429): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4429): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4429): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4429): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4429): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4429): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4429): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4504 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3853
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3853:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 9.921MB for 39954-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4504): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/GAV2    ( 4504): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 9.998MB for 79892-byte allocation
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4504): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4504): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4504): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 10.033MB for 84664-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4504/10151)
,I/ActivityManager(  906): Recipient 3853
,V/WebViewChromiumFactoryProvider( 4504): Binding Chromium to main looper Looper (main, tid 1) {41af31c0}
,I/LibraryLoader( 4504): Expected native library version number "",actual native library version number ""
,I/chromium( 4504): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4504): Initializing chromium process, renderers=0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4314d598): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4504): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(431b3cc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(4314d598): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4504): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4504): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4504): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4504): Local Branch: 
I/Adreno-EGL( 4504): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4504): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4504):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 10.279MB for 75760-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43bff870 u0 ReceiverList{43bff750 4429 com.facebook.katana/10026/u0 remote:43b52310}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43bff870 u0 ReceiverList{43bff750 4429 com.facebook.katana/10026/u0 remote:43b52310}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44040690 u0 ReceiverList{43c48430 4429 com.facebook.katana/10026/u0 remote:44016910}}
,I/NSApplication( 4504): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4504/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4504/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4129/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4129/10160)
,D/Process (  906): killProcessQuiet, pid=3984
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3984:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,D/PMS     (  906): acquireWL(43b08940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,D/PMS     (  906): releaseWL(43b08940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCoreFlp( 1430): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(4352fb20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
D/PMS     (  906): releaseWL(4352fb20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1167): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1167): EAPOL: disable timer tick
,I/ActivityManager(  906): Recipient 3984
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4429): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4429): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(43f8de28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19976 delay=15s
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 4151): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/MDST    (  906): default: setTeardownRequested(true)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@424213c8
,D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(437ca420): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4471/10078)
,D/PMS     (  906): acquireWL(43fa6af8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2245 10028 null
I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/PMS     (  906): acquireWL(437021a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2245 10028 null
,D/PMS     (  906): releaseWL(437ca420): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): releaseWL(43fa6af8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/CheckinService( 2245): Preparing to send checkin request
,I/EventLogService( 2245): Accumulating logs since 1452278265924
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
,I/GoogleHttpClient( 2245): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2245): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2245/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2245/10028)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2245): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b34730 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 6 3 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4579 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4579): install
,I/MultiDex( 4579): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4579): loading existing secondary dex files
,I/MultiDex( 4579): load found 1 secondary dex files
,I/MultiDex( 4579): install done
,I/ProviderInstaller( 4579): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4579): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4579): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4579): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4579): Local Branch: 
I/Adreno-EGL( 4579): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4579): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4579):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): releaseWL(423b0a58): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  906): NoActiveNetworkState
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/PMS     (  906): acquireWL(434194a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(434194a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
I/acms    ( 1903): Checking Certificates
I/acms    ( 1903): Checking Developer Certificates
I/acms    ( 1903): Checking Application Certificates
I/acms    ( 1903): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1903): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1903): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1903): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1903): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1903): Updating next query delay: 75600000
I/mlserverapp( 1903): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1903): cancelACMSProgrammedChecks
,I/NetworkMonitor( 3873): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4471/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1903/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3873/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3895/10051)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
D/PMS     (  906): acquireWL(42e459c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
D/PMS     (  906): releaseWL(42e459c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2028/10021)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42372e70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2245 10028 null
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42372e70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
,D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =411b +++++
,D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(421aa4f0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1367 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
,D/AutoSetting( 1399): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4471): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4471): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4504/10151)
D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1399): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1399): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1399): service - handleMessage() setting current location null
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1399): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [3][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4129/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4129/10160)
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 210
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,I/dalvikvm-heap( 4129): Grow heap (frag case) to 13.522MB for 1821008-byte allocation
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): acquireWL(424607c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  906): releaseWL(424607c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4579/10028)
,I/Adreno-EGL( 4579): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4579): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4579): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4579): Local Branch: 
I/Adreno-EGL( 4579): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4579): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4579):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4579): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4579): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4579): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4579): Local Branch: 
I/Adreno-EGL( 4579): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4579): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4579):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=33 [6][2][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-53 , oldRssi= -200
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/Settings( 4579): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/GCM     ( 1367): Connected
D/PMS     (  906): acquireWL(423f15f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): releaseWL(421aa4f0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): releaseWL(423f15f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(42684f30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1367): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
D/PMS     (  906): releaseWL(42684f30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(43340ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  906): releaseWL(43340ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/CheckinTask( 2245): Sending checkin request (8960 bytes)
D/libc    ( 2245): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2245): [NET] getaddrinfo-,err=8
D/libc    ( 2245): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2245): [NET] getaddrinfo-, 1
D/libc    ( 2245): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6a64 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,W/fb4a(:<default>):UserScope( 4429): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4429): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 46
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2245): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/libc    ( 2245): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2245): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4429): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=12 [16][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  906): releaseWL(431b3cc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  906): acquireWL(43803c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  906): releaseWL(43803c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2245/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2245/10028)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2245): awaiting user notification for token
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b3b5d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 7 2 12
,I/CheckinTask( 2245): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2245): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(437021a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/GCM     ( 1367): GCM config loaded
E/ActivityThread( 2245): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c63aa8 that was originally bound here
E/ActivityThread( 2245): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c63aa8 that was originally bound here
E/ActivityThread( 2245): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2245): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2245): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2245): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2245): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2245): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2245): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2245): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2245): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2245): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2245): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2245): 	at bks.a(SourceFile:298)
E/ActivityThread( 2245): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2245): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2245): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2245): 	at java.lang.Thread.run(Thread.java:864)
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =2217 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 7
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175,
,I/SensorManager(  906): mEventCount = 1350
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420b6f70
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420b6f70, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42134c38
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@422f1088
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/PMS     (  906): mWirelessDisplayManager is null
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/GAV2    ( 4504): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(4400be48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  906): acquireWL(430b3cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  906): releaseWL(4400be48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(430b3cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 384ms
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425af278)
,D/NfcService( 1254): applyRouting -2
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4373
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(425af1d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  906): releaseWL(425af1d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  906): acquireWL(43fcdbe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [4][0][0]
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  906): releaseWL(43fcdbe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/MtpService( 2028): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1254): applyRouting - 0
D/MtpService( 2028): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting -2
,D/AutoSetting( 1399): receiver - intent: android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/PMS     (  906): acquireWL(43b0f420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
D/PMS     (  906): releaseWL(43b0f420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/HtcPowerSaver(  906): << updateStatus
,D/WifiNative-wlan0(  906):    returned true
,D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19977 delay=15s
D/TetherSettings( 4151): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4151): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4151): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4151): Cust_ConnectToPC   : spcsc>false
D/        ( 4151): Cust_ConnectToPC   : IPT>true
D/        ( 4151): Cust_ConnectToPC   : Singel_USB>false
I/ClockThread( 1117): stop update clock
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:On
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
W/Settings( 4151): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4151): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4151): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4151): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
I/PSReceiver( 4151): onReceive:android.intent.action.USER_PRESENT
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/SmartNS_PSService( 4151): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/Settings( 4151): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4151):  defaultType:0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/ContextImpl( 4151): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiNative-wlan0(  906):    returned true
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:42, mTXpacketCount:0, avgLinkspeed:72,mAvgTxRate54
D/WifiStateMachine(  906): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
D/NetworkPolicy(  906): updateScreenOn: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4628 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/ContextImpl( 4628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1847): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1847): onScreenOn: 1452278322756
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1847): onScreenOn: 1452278322756
D/PMS     (  906): acquireWL(42eb5ce0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
D/PMS     (  906): releaseWL(42eb5ce0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42134c38
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
D/SmartSyncUtils( 4628): isEpsOn(), nState = 0
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42134c38, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@422f1088
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  906): acquireWL(437d97d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4628 1000 null
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43f13cb8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): releaseWL(437d97d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
,I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19977 mDataStallAlarmIntent=PendingIntent{43ff41f0: PendingIntentRecord{4245fee8 android broadcastIntent}}
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:Off
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1167): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(43fd1250): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4628): getMobilePolicyEnabled, result = true
D/NetworkPolicy(  906): updateScreenOn: false
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  906): killProcessQuiet, pid=4233
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4233:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4233
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43fd1250): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl( 4628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4628): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4628): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4628): isEpsOn(), nState = 0
,D/ContactMessageStore( 1241): start background delete task...
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422f1088
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422f1088, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422f1088, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422f1088
D/WifiService(  906): New client listening to asynchronous messages
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4247ab38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4247ab38 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1847): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1847): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1847): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1847): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1847): onScreenOff
D/PMS     (  906): acquireWL(43fe0060): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
D/PMS     (  906): releaseWL(43fe0060): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1399): service - mHandler: cancel location update
,D/AutoSetting( 1399): service -           changes count: 0
,I/jxcore-log( 4373): Test app app.js loaded
I/jxcore-log( 4373): 
,I/Choreographer( 4373): Skipped 534 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4373): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4373): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41afb2f8 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4373): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  906): releaseWL(43f13cb8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/Process (  906): killProcessQuiet, pid=4264
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4264:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4264
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4287
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4287:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4287
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 10.943MB for 10918-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 10.953MB for 16372-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 10.966MB for 24554-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 10.986MB for 36826-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 11.014MB for 55234-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4429/10026)
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 11.131MB for 92026-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 11.138MB for 61910-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 11.179MB for 78772-byte allocation
,D/libc    ( 4429): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4429): [NET] getaddrinfo-,err=8
D/libc    ( 4429): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4429): [NET] getaddrinfo-, 1
,D/libc    ( 4429): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5a8a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 14
,D/libc    (  365): [NET]res_nsend:resplen=93
D/libc    (  365): [NET]res_queryN: exit 3, ancount=3
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4429): [NET] getaddrinfo_proxy-, success
I/global  ( 4429): call createSocket() return a new socket.
D/libc    ( 4429): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4429): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4429): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4429): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(43437180): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4429 10026 null
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4429): I/O error closing connection
I/global  ( 4429): java.net.SocketException: Socket is closed
I/global  ( 4429): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4429): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4429): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4429): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4429): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4429): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4429): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4429): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4429): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4429): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4429): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4429): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4429): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4429): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4429): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4429): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4429): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4429): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4429): Removing a connection that never existed!
D/PMS     (  906): releaseWL(43437180): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{435e07b0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42fa81c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d5d88: PendingIntentRecord{42337ea0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=128508, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42fa81c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437ebb88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(437ebb88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1399): service - mHandler: update timezone
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onCreate()
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1590): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1519): service - mHandler: update timezone
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e8f640 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 1399): service - handleMessage() stop self
,D/AutoSetting( 1399): service - onDestroy() END
,D/AutoSetting( 1399): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=3895
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3895:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3895
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(43ff71d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{4239d5e8: PendingIntentRecord{4258e268 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141390, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{424261c0: PendingIntentRecord{423d5ef0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141483, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
,V/AlarmManager(  906): sending alarm PendingIntent{41da13e8: PendingIntentRecord{4248d2c8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=152511, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(43fe2280): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): acquireWL(43fd2850): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  906): acquireWL(43fc60a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(43ff71d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(43fd2850): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6237 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(43f2f0d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43fc60a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43f2f0d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42e80d78 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): releaseWL(43fe2280): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4305
,I/ActivityManager(  906): Killing 4305:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4305
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43440308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PMS     (  906): releaseWL(43440308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(43101068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{420d5d88: PendingIntentRecord{42337ea0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=188509, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43101068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(430bd600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(430bd600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42d5a780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43f64248: PendingIntentRecord{438551b0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=225905, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4667 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{425498c0: PendingIntentRecord{42005d70 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452278432037, Int=10800000
,D/PMS     (  906): releaseWL(42d5a780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4667/10047)
,D/Process (  906): killProcessQuiet, pid=4321
,I/ActivityManager(  906): Killing 4321:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4321
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
,D/PMS     (  906): acquireWL(420a2c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{41ec5438: PendingIntentRecord{438551b0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231291, Int=0
,D/PMS     (  906): releaseWL(420a2c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  906): acquireWL(41de0b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(41de0b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(41c22298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{420d5d88: PendingIntentRecord{42337ea0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=248508, Int=0
,D/PMS     (  906): releaseWL(41c22298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(422d9028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(422d9028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(4246c378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(4246c378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4373): --= Surplus to requirements =--
I/jxcore-log( 4373): 
I/jxcore-log( 4373): ****TEST TOOK:  ms ****
I/jxcore-log( 4373): 
,I/jxcore-log( 4373): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4373): 
,E/cutils-trace( 4691): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4691): ====startRecUseTime====
D/htc.customization.log.level( 4691):  is 
,W/CustomizationLogLevel( 4691): Level value is invalid, use default level 2
,D/CustomizationManager( 4691):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 4691): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4691): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4691): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4691): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4691): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4691): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4691): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4691): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4691): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4691): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4691): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4691): Parsing tag category name = system
,I/CustomizationCIDLoader( 4691): Parsing tag category name = application
I/CustomizationCIDLoader( 4691): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4691): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4691): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4691): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4691): Parsing tag category name = Settings
D/CustomizationManager( 4691):  Read CID file spent 0.158 (s)
,D/CustomizationManager( 4691):  All configurations done spent 0.158 (s)
,W/HtcNativeFlag( 4691): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4691): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4691): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4691): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4691, uid=2000 user=0
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=4373
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906): Killing 4373:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  906):   Force finishing activity ActivityRecord{423026e8 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  906): Copying FileAsset 0x62d10fa0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  906): channel '424a7ab0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  906): channel '424a7ab0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '424a7ab0 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  906): WIN DEATH: Window{424a7ab0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  906): Client connection lost with reason: 4
I/WindowManager(  906): WINDOW DIED Window{424a7ab0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4373 uid 10348
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
W/PackageSettings(  906): Skipping PackageSetting{422d19a8 com.example.hello/10356} due to missing metadata
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
,I/dalvikvm-heap( 4129): Grow heap (frag case) to 15.209MB for 1821008-byte allocation
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/acms    ( 1903): Unregistering com.test.thalitest
E/acms    ( 1903): Could not unregister removed application com.test.thalitest
,D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1430): Ignoring removeGeofence because network location is disabled.
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): acquireWL(43ea1ff0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
D/PMS     (  906): releaseWL(43ea1ff0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  906):   Scheme: "sms"
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/Launcher( 1271): Deferring update until onResume
,D/Launcher( 1271): waitUntilResume // bindAppsRemoved
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
,D/PackageBroadcastService( 2245): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4706 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/MultiDex( 4706): install
,I/MultiDex( 4706): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4706): loading existing secondary dex files
,I/MultiDex( 4706): load found 1 secondary dex files
,I/MultiDex( 4706): install done
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4722 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PeopleContactsSync( 2245): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2245, uid=10028, userID:0
,D/PMS     (  906): acquireWL(420a2c48): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
I/Icing   ( 2245): doRemovePackageData com.test.thalitest
,I/ProviderInstaller( 4706): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  906): releaseWL(420a2c48): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4722): install
,I/MultiDex( 4722): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4722): loading existing secondary dex files
,I/MultiDex( 4722): load found 1 secondary dex files
,I/MultiDex( 4722): install done
,I/ProviderInstaller( 4722): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  906): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1399): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1399): handle notify Blinkfeed plugin client changed
,D/Process (  906): killProcessQuiet, pid=4337
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  906): Killing 4337:com.android.settings:remote/1000 (adj 15): empty #17
,I/IcingCorporaProvider( 2914): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4743 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,W/PackageManager(  906): Unable to load service info ResolveInfo{421acbe8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/ActivityManager(  906): Recipient 4337
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(425b86e0): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
,I/IcingCorporaProvider( 2914): UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
,E/SQLiteLog( 4706): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4706): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca4f988
,E/DriveAsyncService( 4706): disk I/O error (code 3850)
E/DriveAsyncService( 4706): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4706): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4706): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4706): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4706): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4706): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4706): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4706): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4706): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4706): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4706): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4706): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4706): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4706): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4706): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4706): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca4f988
,E/DocListDatabase( 4706): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4706): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4706): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4706): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4706): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4706): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4706): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4706): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4706): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4706): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4706): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4706): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4706): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4706): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4706): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4706): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4706): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4706): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4706): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4706): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4706): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4706): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4706): threadid=1: thread exiting with uncaught exception (group=0x416bde30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
,D/Process ( 4706): killProcess, pid=4706
,D/Process ( 4706): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 4706): FATAL EXCEPTION: main
E/AndroidRuntime( 4706): Process: com.google.android.gms.drive, PID: 4706
E/AndroidRuntime( 4706): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4706): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4706): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4706): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4706): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4706): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4706): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4706): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4706): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4706): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4706): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4706): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4706): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4706): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4706): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4706): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4706): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4706): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4706): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4706): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4706): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4706): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4706): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4706): 	... 10 more
,E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4706
,I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4706) has died.
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
,E/SQLiteDatabase( 4743): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4743): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4743): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4743): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4743): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4743): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4743): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4743): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4743): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4743): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4743): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4743): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4743): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4743): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4743): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4743): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4743): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4743): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4743): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4743): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4743): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4743): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4743): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4743): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4743): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4743): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4743): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4743): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4743): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4743): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4743): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4743): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4743): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4743): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4743): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4743): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4743): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4743): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4743): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4743): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4743): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4743): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4743): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4743): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4743): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4743): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4743): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4743): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4743): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4743): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4743): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4743): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4743): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4743): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4743): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4743): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4743): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4743): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4743): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4743): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4743): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4743): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4743): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4743): threadid=11: thread exiting with uncaught exception (group=0x416bde30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4743): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4743): Process: com.google.android.apps.docs, PID: 4743
E/AndroidRuntime( 4743): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4743): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4743): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4743): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4743): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4743): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4743): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4743): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4743): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 4743): killProcess, pid=4743
D/Process ( 4743): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4764 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4743
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4251
,I/ActivityManager(  906): Killing 4251:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4743) has died.
,I/ActivityManager(  906): Recipient 4251
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4764): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4764): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4764): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4764): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4764): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4764): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4764): threadid=10: thread exiting with uncaught exception (group=0x416bde30)
,E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4764): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4764): Process: com.android.keychain, PID: 4764
E/AndroidRuntime( 4764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4764): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4764): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4764): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4764): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4777 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4764): killProcess, pid=4764
,D/Process ( 4764): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452278511532.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  906): Recipient 4764
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4764) has died.
,W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10649ms
,D/AppTag  ( 4777): getInstance(Context context)
,D/AppTag  ( 4777): getInstance(Context context)
,D/AppTag  ( 4777): onCreate()
,D/PMS     (  906): acquireWL(425cc2f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4129 10160 null
,I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4795 uid=10098 gids={50098, 3003, 5012}
,I/dalvikvm-heap( 4129): Grow heap (frag case) to 16.949MB for 1821008-byte allocation
D/PMS     (  906): releaseWL(425cc2f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/DeviceManagement( 4795): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4795 dbg=false s=true
,I/DeviceManagement( 4795): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4795): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4795): WorkflowService: Starting workflow service
I/DeviceManagement( 4795): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b20020] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4795): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4795): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4795): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4795): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4809 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4795): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4795): SessionStateController: Checking invariants...
,D/Documents( 4809): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4809): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4809): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4809): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4809): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4809): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4809): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4809): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4809): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4809): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4809): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4809): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4809): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4809): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4809): threadid=1: thread exiting with uncaught exception (group=0x416bde30)
E/AndroidRuntime( 4809): FATAL EXCEPTION: main
E/AndroidRuntime( 4809): Process: com.android.documentsui, PID: 4809
E/AndroidRuntime( 4809): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4809): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4809): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4809): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4809): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4809): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4809): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4809): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4809): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4809): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4809): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4809): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4809): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4809): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4809): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4809): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4809): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4809): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4809): 	... 10 more
I/ActivityManager(  906): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4823 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process (  906): killProcessQuiet, pid=4441
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  906): App crashed! Process: com.android.documentsui
I/ActivityManager(  906): Killing 4441:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Process ( 4809): killProcess, pid=4809
,D/Process ( 4809): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4441
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452278511865.dbox_tmp: open failed: EROFS (Read-only file system)
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
,D/Process (  906): killProcessQuiet, pid=3873
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  906): Killing 3873:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  906): Recipient 4809
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b80dd0 +
I/ActivityManager(  906): Process com.android.documentsui (pid 4809) has died.
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/Prism.WidgetManager( 1271): onLoadItems() +
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ExternalStorage( 4823): After updating volumes, found 1 active roots
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,E/SQLiteDatabase( 4795): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4795): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4795): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4795): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4795): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4795): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4795): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4795): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4795): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4795): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4795): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4795): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4795): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4795): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4795): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4795): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4795): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4795): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4795): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4795): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4795): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4839 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4795): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4795): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4795): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4795): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4795): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4795): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4795): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4795): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4795): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4795): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4795): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4795): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4795): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/DeviceManagement( 4795): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b20020]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4795): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4795): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4795): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4795): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4795): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4795): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4795): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4795): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4795): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4795): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4795): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 4795): WorkflowService: Stopping workflow service
I/ActivityManager(  906): Recipient 3873
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3873): Died!
,E/SQLiteDatabase( 4839): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4839): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4839): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4839): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4839): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4839): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4839): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4839): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Icing   ( 2245): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
,E/SQLiteOpenHelper( 4839): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4839): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4839): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4839): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4839): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4839): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4839): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4839): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4839): Opened MyDB.db in read-only mode
,D/Process (  906): killProcessQuiet, pid=4471
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4471:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4471
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 2245): Could not init tag ds.tag.deleted

```
