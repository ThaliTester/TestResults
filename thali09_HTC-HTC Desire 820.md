#### Test 55613145b105d0b_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/IcingCorporaProvider( 2838): UpdateCorporaTask done [took 960 ms] updated apps [took 960 ms] 
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b9dbd0 +
I/Prism.WidgetManager( 1277): onLoadItems() +
E/cutils-trace( 4612): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4612): ====startRecUseTime====
D/htc.customization.log.level( 4612):  is 
W/CustomizationLogLevel( 4612): Level value is invalid, use default level 2
I/Icing   ( 2181): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
D/CustomizationManager( 4612):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4612): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4612): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4612): Parsing tag category name = system
I/CustomizationCIDLoader( 4612): Parsing tag category name = application
I/CustomizationCIDLoader( 4612): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4612): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4612): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4612): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4612): Parsing tag category name = Settings
D/CustomizationManager( 4612):  Read CID file spent 0.100 (s)
D/CustomizationManager( 4612):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 4612): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4612): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4612): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4612): Fail to get flag for type 'language', use default value: -1
I/Icing   ( 2181): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
--------- beginning of /dev/log/system
D/PMS     (  910): releaseWL(44243878): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  910): start
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4612
D/PMS     (  910): acquireHCC(42522328): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(424cba70): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
E/Prism.WidgetManager( 1277): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1277): onLoadItems() -
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b9dbd0 -
W/asset   (  910): Copying FileAsset 0x67c29f90 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1113261736
I/FeedHostManager( 1277): [onPause]
I/FeedProviderManager( 1277): onPause
I/FeedHostManager( 1277): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4204c468
I/SocialFeedProvider( 1277): +onPause
I/SocialFeedProvider( 1277): -onPause
D/PMS     (  910): acquireWL(43554028): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4623 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/GCoreNlp( 1228): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/asset   ( 4623): Copying FileAsset 0x5c851428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  910): acquireWL(430bb748): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(430bb748): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/TrimMemoryManager( 1277): [trimMemory] 20
D/PMS     (  910): acquireWL(43ba0710): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43ba0710): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  910): applying state to connected service
D/LocationProviderProxy(  910): applying state to connected service
V/WebViewChromiumFactoryProvider( 4623): Binding Chromium to main looper Looper (main, tid 1) {41b0c480}
I/LibraryLoader( 4623): Expected native library version number "",actual native library version number ""
I/chromium( 4623): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4623): Initializing chromium process, renderers=0
D/PMS     (  910): acquireWL(4369ca98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4369ca98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42bac410): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42bac410): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4413c578:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4623): 1102192312: getState(). Returning 12
D/PMS     (  910): acquireWL(425f8978): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): acquireWL(43451468): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): releaseWL(425f8978): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4623): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4623): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4623):                  aa63bbd948f41d15fc72f585e
W/chromium( 4623): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4623): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4623): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4623): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4623): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4623): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4623): CordovaWebView is running on device made by: HTC
,W/AwContents( 4623): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  910): Disable input method client, pid=1277
W/ResourceType( 4623): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4623): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b53568, mServedView=org.apache.cordova.engine.SystemWebView{41b191d0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  910): Enable input method client, pid=4623
W/AwContents( 4623): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +292ms
D/PMS     (  910): releaseWL(43554028): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/PhoneApp( 1248): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1248): -- N1 =0
D/PhoneApp( 1248): -- N2 =0
D/PhoneApp( 1248): -- N3 =0
D/JsMessageQueue( 4623): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4623): JniHelper::setJavaVM(0x415e2048), pthread_self() = 1663150352
D/JX-Cordova( 4623): jxcore cordova android initializing
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 26
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 78
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 11.584MB for 95956-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 11.664MB for 143930-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 11.779MB for 215890-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 11.954MB for 323830-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 12.226MB for 485740-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 13.226MB for 1092904-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 14.093MB for 1639352-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 15.453MB for 2459024-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 17.424MB for 3688532-byte allocation
,W/jxcore-log( 4623): Initializing JXcore engine
,W/jxcore-log( 4623): JXcore engine is ready
,W/jxcore-log( 4623): Starting JXcore engine
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
D/PMS     (  910): releaseHCC(42522328): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  910): releaseHCC(424cba70): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4623): Platform android
W/jxcore-log( 4623): 
,W/jxcore-log( 4623): Process ARCH arm
W/jxcore-log( 4623): 
,I/SensorManager(  910): mEventCount = 1350
,I/jxcore-log( 4623): JXcore Cordova bridge is ready!
I/jxcore-log( 4623): 
,W/jxcore-log( 4623): JXcore engine is started
,I/chromium( 4623): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4623): Toggling radios to true
I/jxcore-log( 4623): 
,D/BluetoothAdapter( 4623): enable(): BT is already enabled..!
,D/WifiManager( 4623): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
,W/Settings:Agent(  910): Process.myTid(): 1273
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 5(ms)
,D/WifiManager( 4623): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  910): New client listening to asynchronous messages
D/WifiService(  910): setWifiEnabled: true pid=4623, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiManager( 4623): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): TDLS: Tear down peers
I/wpa_supplicant( 1162): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4623): Radios toggled
I/jxcore-log( 4623): 
I/jxcore-log( 4623): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4623): 
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1162): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1162): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
,D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): TDLS: Remove peers on disassociation
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb709dbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1162): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  910): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  910):    returned true
D/WifiPerfLock(  910): release(),
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(44172a68): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-wlan0(  910): doBoolean: RECONNECT
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19753 mDataStallAlarmIntent=PendingIntent{43b6cbc0: PendingIntentRecord{424f8778 android broadcastIntent}}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): Fast associate: Old scan results
I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3810): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3810): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  910): New client listening to asynchronous messages
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,V/NativeCrypto( 1365): Read error: ssl=0x66117430: I/O error during system call, Connection timed out
D/libc    (  362): [NET] entry_id:3   entry:0xb7d61220  removed 
D/libc    (  362): [NET] entry_id:7   entry:0xb7d61738  removed 
D/libc    (  362): [NET] entry_id:8   entry:0xb7d615e0  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb7d60fd8  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb7d612f8  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb7d61428  removed 
D/libc    (  362): [NET] entry_id:6   entry:0xb7d61860  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb7d610e8  removed 
D/libc    (  362): [NET] entry_id:9   entry:0xb7d61670  removed 
,D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
,D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/WISPrService( 3810): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3810): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
D/WifiNative-wlan0(  910): doBoolean: SCAN
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  910): acquireWL(43c3cc48): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(434bbed8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/BatSI   (  910): WIFI scan started for: 650a0300 uid:1000
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  910):    returned false
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,D/PMS     (  910): releaseWL(434bbed8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
,V/NativeCrypto( 1365): SSL shutdown failed: ssl=0x66117430: I/O error during system call, Broken pipe
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1365/10029)
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/PMS     (  910): releaseWL(43c3cc48): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): releaseWL(43451468): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4676 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ConnectivityHelper( 1277): [onReceive] WIFI(1): DISCONNECTED
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(426eb208): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1277/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4421/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4421/10100)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
D/PMS     (  910): releaseWL(426eb208): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,I/MusicStore( 4676): Database version: 95
,W/ContextImpl( 4676): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4676): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4676): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4218f648
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4218f648, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fb6418
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@41c234e0
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4676): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4676): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/PMS     (  910): mWirelessDisplayManager is null
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4676, uid=10154, userID:0
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 319ms
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43ba7c80)
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
D/PMN     (  910): wakingUp
,I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
D/NfcService( 1261): applyRouting - 0
D/NfcService( 1261): ScreenObserver: OFF
,D/NfcService( 1261): applyRouting -2
D/PMS     (  910): acquireWL(426393e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
D/PMS     (  910): releaseWL(426393e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputMethodManagerService(  910): Disable input method client, pid=4623
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/WindowManager(  910): No lock screen! windowToken=null
D/PMN     (  910): onScreenOn
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
D/PMS     (  910): acquireWL(43100018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43100018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/MtpService( 1949): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1949): [MTP][onReceive]-
,D/NfcService( 1261): applyRouting - 0
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/NfcService( 1261): applyRouting -2
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
D/PMS     (  910): acquireWL(43223ee8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
D/PMS     (  910): releaseWL(43223ee8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:On
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 1162): wpa_supplicant_scan enter
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WifiNative-wlan0(  910):    returned true
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
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
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/ClockThread( 1119): stop update clock
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): acquireWL(4374e3f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4374e3f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43164568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1762): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1762): onScreenOn: 1452763934972
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1762): onScreenOn: 1452763934972
D/PMS     (  910): releaseWL(43164568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fb6418
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fb6418, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@41c234e0
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(43c4f150): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19754 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='1'
D/PMS     (  910): acquireWL(431f8070): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1162): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1162): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 3
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 1
I/wpa_supplicant( 1162): wpa_s->is_screen_on 1
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1162): selected network = 2
D/wpa_supplicant( 1162): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb709f4e8  current_ssid=0x0
D/wpa_supplicant( 1162): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1162): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1162): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1162): check if in concurrent case
,I/wpa_supplicant( 1162): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1162): RSN: PMKSA cache search - network_ctx=0xb709f4e8 try_opportunistic=0
D/wpa_supplicant( 1162): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1162): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1162): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1162): nl80211: Unsubscribe mgmt frames handle 0xb709e718 (mode change)
D/wpa_supplicant( 1162): nl80211: Subscribe to mgmt frames with non-AP handle 0xb709e718
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb709e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1162):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162):   * freq=2412
D/wpa_supplicant( 1162):   * Auth Type 0
D/wpa_supplicant( 1162):   * WPA Versions 0x2
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1162): nl80211: Connect request send successfully
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:Off
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 116,2): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1162): get_ip_address source addr = 02000000
I/wpa_supplicant( 1162): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
V/SRS_Proc(  370): ParamSet string: screen_state=off
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1162): reply (613) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-46
I/wpa_supplicant( 1162): tsf=0000000021859870
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-59
I/wpa_supplicant( 1162): tsf=0000000021859880
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=2
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-59
I/wpa_supplicant( 1162): tsf=0000000104742657
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2452
I/wpa_supplicant( 1162): level=-85
I/wpa_supplicant( 1162): tsf=0000000021859889
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=b8:bc:1b:5a:18:00
I/wpa_supplicant( 1162): freq=2452
I/wpa_supplicant( 1162): level=-89
I/wpa_supplicant( 1162): tsf=0000000021859894
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=HUAWEI-1800
I/wpa_supplicant( 1162): ####
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
D/PMS     (  910): releaseWL(431f8070): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (5) end of scan result ==
D/WifiManager( 1228): getScanResults enter 
D/ContactMessageStore( 1248): start background delete task...
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 21859870, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 21859880, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 104742657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2452, timestamp: 21859889, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/NetworkPolicy(  910): updateScreenOn: false
D/WifiStateMachine(  910): 4: scan result = SSID: HUAWEI-1800, BSSID: b8:bc:1b:5a:18:00, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2452, timestamp: 21859894, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 5 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ContactMessageStore( 1248): size: 0 , 0
D/ContactMessageStore( 1248): Background delete complete
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (5) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
I/MediaRouter( 4676): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/MediaRouterService(  910): Client com.google.android.music (pid 4676): Registered
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4676/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1949/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4705 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4676): getSelectedRoute
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4676/10154)
,I/NetworkMonitor( 4676): type=WIFI subType= reason=null isConnected=false
D/PMS     (  910): acquireWL(436ff0b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(436ff0b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
D/PMS     (  910): acquireWL(4407ec78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4407ec78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4676, uid=10154, userID:0
,D/ACRA    ( 4705): ACRA is enabled for com.facebook.katana, intializing...
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Connect event
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1162): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Add randomness: count=9 entropy=1
I/wpa_supplicant( 1162): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): TDLS: Remove peers on association
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1162): EAPOL: enable timer tick
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1162): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1162): Get randomness: len=32 entropy=2
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4,:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1762): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1762): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1762): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1762): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1762): onScreenOff
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42742f60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(42742f60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb709e9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f8cb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1162):    broadcast key
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1162): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1162): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Process (  910): killProcessQuiet, pid=4248
I/wpa_supplicant( 1162): State: GROUP_HANDSHAKE -> COMPLETED
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiStateMachine(  910): This record is existed, only update it...
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1162): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/ACRA    ( 4705): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1162): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=6
D/ACRA    ( 4705): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/wpa_supplicant( 1162): set send_ind_to_ndc = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1162): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1162): EAPOL authentication completed successfully
I/wpa_supplicant( 1162): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1162): send_and_recv error, 0 - cmd 79
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,I/ActivityManager(  910): Killing 4248:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,I/ActivityManager(  910): Recipient 4248
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
,W/SystemClassLoaderAdder( 4705): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4705): Preparing secondary program dexes.
V/DexLibLoader( 4705): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4705): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4705): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4705): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4705): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,D/WISPrService( 3810): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3810): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,W/DexLibLoader( 4705): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4705): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4705): Dex already copied
D/OdexVerifier( 4705): Odex verification is skipped.
,V/DexLibLoader( 4705): Creating class loader
,V/DexLibLoader( 4705): Finished creating class loader
V/DexLibLoader( 4705): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4705): Dex already copied
D/OdexVerifier( 4705): Odex verification is skipped.
,V/DexLibLoader( 4705): Creating class loader
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
V/DexLibLoader( 4705): Finished creating class loader
V/DexLibLoader( 4705): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4705): Dex already copied
D/OdexVerifier( 4705): Odex verification is skipped.
V/DexLibLoader( 4705): Creating class loader
V/DexLibLoader( 4705): Finished creating class loader
V/DexLibLoader( 4705): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4705): Dex already copied
D/OdexVerifier( 4705): Odex verification is skipped.
V/DexLibLoader( 4705): Creating class loader
V/DexLibLoader( 4705): Finished creating class loader
V/DexLibLoader( 4705): Verifying classes from secondary dexes.
D/DexLibLoader( 4705): DexLibLoader.ensureDexLoaded took 18 ms
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1162): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 1
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(437546e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1162): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4232b288 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4232b288 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{41db9cb0 u0 com.test.thalitest/.MainActivity t2}
,W/dalvikvm( 4705): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4705): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4705): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4705): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4705): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4705): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4705): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4705): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1162): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1162): EAPOL: disable timer tick
,W/dalvikvm( 4705): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4705): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4705): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4705): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4705): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4705): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=4421
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4421:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1317): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4744 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
,D/AutoSetting( 1317): Util - no network available!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
,D/AutoSetting( 1317): service - onCreate()
,D/AutoSetting( 1317): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  910): request 41dfd610 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1317): service - mHandler: cancel location update
,D/AutoSetting( 1317): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4705): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4705): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4744): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4744): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4744): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4744): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4705): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4771 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4744/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4744/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4744/10079)
,I/ActivityManager(  910): Recipient 4421
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4785 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=4438
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 4438:com.htc.backup/1000 (adj 15): empty #17
,E/dalvikvm( 4705): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4705): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4705): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4705): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4705): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4705): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
I/ActivityManager(  910): Recipient 4438
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/dalvikvm( 4705): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4705): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4705): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4705): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4705): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4705): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  910): releaseWL(437546e0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/dalvikvm-heap( 4705): Grow heap (frag case) to 9.959MB for 84664-byte allocation
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1162): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/dalvikvm( 4705): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4705): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/dalvikvm( 4705): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4705): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
W/dalvikvm( 4705): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4705): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,W/ContextImpl( 4785): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/WifiWatchdogStateMachine(  910): WAN detection
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4785): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42494028
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3810): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1162): Change stage from stage0 to stage3
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/WifiStateMachine(  910): syncGetConfiguredNetworks
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/dalvikvm-heap( 4705): Grow heap (frag case) to 9.972MB for 28144-byte allocation
,W/GAV2    ( 4785): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(42668138): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4744/10079)
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,W/ContextImpl( 4785): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,W/ContextImpl( 4785): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/PMS     (  910): acquireWL(42580848): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
,I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,I/dalvikvm-heap( 4705): Grow heap (frag case) to 10.013MB for 39954-byte allocation
,I/CheckinService( 2181): Checkin interval check for package: unspecified last checkin: 1452763921343 min interval config: 0 actual interval: 15610
D/PMS     (  910): acquireWL(43bc4308): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42580848): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2181): Checking schedule, now: 1452763936962 next: 1452763951317
,I/CheckinService( 2181): active receiver: disabled
I//system/bin/ip(  362): RTNETLINK answers: No such process
I/logwrapper(  362): /system/bin/ip terminated by exit(2)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2181, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
D/PMS     (  910): releaseWL(43bc4308): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
I/dalvikvm-heap( 4705): Grow heap (frag case) to 10.088MB for 79892-byte allocation
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(42668138): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4785/10151)
,V/WebViewChromiumFactoryProvider( 4785): Binding Chromium to main looper Looper (main, tid 1) {41b11108}
,I/LibraryLoader( 4785): Expected native library version number "",actual native library version number ""
,I/chromium( 4785): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4785): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(4379d938): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  910): acquireWL(44187b90): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4785): BLUETOOTH permission is missing!
D/PMS     (  910): releaseWL(4379d938): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4785): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4785): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4785): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4785): Local Branch: 
I/Adreno-EGL( 4785): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4785): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4785):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4785): Starting up...
,I/dalvikvm-heap( 4705): Grow heap (frag case) to 10.276MB for 75760-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4785/10151)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4785/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4238e238 u0 ReceiverList{421592c8 4705 com.facebook.katana/10027/u0 remote:442d4b58}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4238e238 u0 ReceiverList{421592c8 4705 com.facebook.katana/10027/u0 remote:442d4b58}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{439cd638 u0 ReceiverList{439cd5d8 4705 com.facebook.katana/10027/u0 remote:43124630}}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/Process (  910): killProcessQuiet, pid=4408
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4109/10160)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4109/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,I/ActivityManager(  910): Killing 4408:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
I/ActivityManager(  910): Recipient 4408
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4835 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): acquireWL(430b9410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(430b9410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3810): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3810): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3810): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3810): Cust_ConnectToPC   : spcsc>false
D/        ( 3810): Cust_ConnectToPC   : IPT>true
,D/        ( 3810): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3810): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3810): Index of the first 1 = -1
W/Settings( 3810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3810): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3810): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3810): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3810): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3810): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3810): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  910): killProcessQuiet, pid=4462
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AutoSetting( 1317): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3810): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3810): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3810): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3810): Cust_ConnectToPC   : spcsc>false
D/        ( 3810): Cust_ConnectToPC   : IPT>true
D/        ( 3810): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3810): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3810): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3810): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/ActivityManager(  910): Killing 4462:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/PSReceiver( 3810): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 3810): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3810):  defaultType:0
W/ContextImpl( 3810): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Recipient 4462
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 4705): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/SmartSyncUtils( 4835): isEpsOn(), nState = 0
,W/ContextImpl( 4705): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/PMS     (  910): acquireWL(429d2340): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4835 1000 null
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4705): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/SmartSyncUtils( 4835): getMobilePolicyEnabled, result = true
D/PMS     (  910): releaseWL(429d2340): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4835): isEpsOn(), nState = 0
D/SmartSyncUtils( 4835): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4835): isEpsOn(), nState = 0
D/WifiService(  910): New client listening to asynchronous messages
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c234e0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c234e0, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c234e0, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c234e0
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@423e8c50 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@423e8c50 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): releaseWL(44172a68): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)},
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/CaptivePortalTracker(  910): NoActiveNetworkState
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
V/Tethering(  910): bSetPropertyMultiRAB:false
I/NetworkMonitor( 4676): type=WIFI subType= reason=null isConnected=true
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/ConnectivityHelper( 1277): [onReceive] WIFI(1): CONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4676/10154)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1277/10076)
D/PMS     (  910): acquireWL(4314fab0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029),
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3905/10053)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4744/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43cea310): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/PMS     (  910): releaseWL(43cea310): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1949/10021)
D/PMS     (  910): releaseWL(4314fab0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
E/ExternalAccountType( 1341): Unsupported attribute readOnly
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1317): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
D/MobileConnectivityChangeReceiver( 4744): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4744): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1317): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1317): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1317): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4785/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4109/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4109/10160)
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2181, uid=10029, userID:0
I/dalvikvm-heap( 4109): Grow heap (frag case) to 13.623MB for 1821008-byte allocation
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,W/fb4a(:<default>):UserScope( 4705): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4705): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43768048): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4676 10154 null
,W/ContextImpl( 4676): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
I/MusicLeanback( 4676): Conditions not met for autocaching.
,I/MusicLeanback( 4676): Stop autocaching.
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4676, uid=10154, userID:0
D/PMS     (  910): releaseWL(43768048): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4676): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/fb4a(:<default>):LocalFbBroadcastManager( 4705): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4705/10027)
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =5b0 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175
,W/ActivityManager(  910): Sleep timeout!  Sleeping now.
,D/PMS     (  910): releaseWL(43c4f150): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  910): releaseWL(44187b90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4623): Test app app.js loaded
I/jxcore-log( 4623): 
,I/Choreographer( 4623): Skipped 510 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4623): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4623): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4623): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b191d0 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/GAV2    ( 4785): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1532): service - handleMessage() stop self
,D/AutoSetting( 1532): service - onDestroy() END
,I/ActivityManager(  910): Killing 4493:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4493
D/AutoSetting( 1532): service - handleMessage() quit looper
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4493
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  910): killProcessQuiet, pid=3905
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3905:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3905
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(426488d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{436f58b0: PendingIntentRecord{4264ed58 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=116672, Int=0
,D/PMS     (  910): acquireWL(43530a50): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1365): [NET] getaddrinfo-, 1
D/libc    ( 1365): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =ead3 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/PMS     (  910): releaseWL(426488d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 220
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1365): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): acquireWL(436d5138): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): releaseWL(43530a50): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(436d5138): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43cccd50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,D/PMS     (  910): releaseWL(43cccd50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1317): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1317): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1317): service - requestNLP() NetworkLocationProvider not enabled
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=8 [23][2][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  910): acquireWL(4355b130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{43447c10: PendingIntentRecord{426dfa98 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=120582, Int=0
,D/PMS     (  910): releaseWL(4355b130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43d22bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(43422680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43422680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43d22bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(435ae400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,D/PMS     (  910): releaseWL(435ae400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(439e9360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): acquireWL(43178570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(43b7a390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1228): Vacuum at: now=1452763951064 tag=VacuumService
D/PMS     (  910): releaseWL(439e9360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43178570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43d2e850): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,D/PMS     (  910): releaseWL(43d2e850): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43b7a390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4266b970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,D/PMS     (  910): releaseWL(4266b970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(431d9018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(431d9018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{4428e848 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(430fa918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430fa918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED,
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42674a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{425679b8: PendingIntentRecord{42735340 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134901, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{43124738: PendingIntentRecord{426bbd08 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452763951317, Int=522937000
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  910): acquireWL(43561070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=50 [4][2][0]
,D/PMS     (  910): acquireWL(430ec358): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
D/PMS     (  910): releaseWL(42674a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42630fd0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(430ec358): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2181): Checkin interval check for package: unspecified last checkin: 1452763921343 min interval config: 0 actual interval: 43875
,I/CheckinService( 2181): Checking schedule, now: 1452763965230 next: 1452763951317
,I/CheckinService( 2181): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2181, uid=10029, userID:0
,I/CheckinService( 2181): Preparing to send checkin request
,I/EventLogService( 2181): Accumulating logs since 1452763918539
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,D/PMS     (  910): acquireWL(43ca1740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43ca1740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2181): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2181): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  910): acquireWL(43083770): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43561070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4341fe08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,D/PMS     (  910): releaseWL(4341fe08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2181/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PhenotypeConfigurator( 1228): Scheduling Phenotype for one-off execution 1906 seconds from now (1452763965734)
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/GetConfigurationSnapshotOperation( 1228): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1228): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2217119195
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1228): Using platform SSLCertificateSocketFactory
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4548/10029)
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2345513413
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1228): [NET] getaddrinfo-, 1
,D/libc    ( 1228): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =8a2 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 278
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
I/WVCdm   (  370): CdmEngine::CloseSession
,D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1228): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4548): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4548): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4548): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4548): Local Branch: 
I/Adreno-EGL( 4548): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4548): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4548):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4548): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4548): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4548): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4548): Local Branch: 
I/Adreno-EGL( 4548): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4548): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4548):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4548): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4548): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4548): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4548): Local Branch: 
I/Adreno-EGL( 4548): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4548): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4548):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,W/Settings( 4548): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2181): Classify the device as Phone.
,D/PMS     (  910): releaseWL(43083770): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(41b24830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2181): [NET] getaddrinfo-,err=8
D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2181): [NET] getaddrinfo-, 1
,D/libc    ( 2181): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =ed53 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,D/PMS     (  910): releaseWL(41b24830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 231
D/libc    (  362): [NET]res_nsend:resplen=84
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2181): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(4234ac08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1365/10029)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2181): [NET] getaddrinfo-,err=8
,D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2181): [NET] getaddrinfo-,err=8
D/libc    ( 2181): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2181): [NET] getaddrinfo-,err=8
D/PMS     (  910): releaseWL(4234ac08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinTask( 2181): Sending checkin request (12255 bytes)
,D/AutoSetting( 1317): service - mHandler: update timezone
,D/AutoSetting( 1317): service - handleMessage() stop self
,D/AutoSetting( 1317): service - handleMessage() quit looper
,D/AutoSetting( 1317): service - onDestroy() END
,D/AutoSetting( 1532): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1532): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1532): service - onCreate()
D/AutoSetting( 1532): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1532): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1532): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1532): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1532): service - mHandler: update timezone
,D/AutoSetting( 1532): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1532): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1532): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1532): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ee2d80 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 1 7 3 11
,I/CheckinRequestBuilder( 2181): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2181): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2181/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=5 [18][1][0]
,I/CheckinRequestBuilder( 2181): Classify the device as Phone.
,I/CheckinTask( 2181): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2181): Checking schedule, now: 1452763968810 next: 1453286905801
,I/CheckinService( 2181): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2181, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024155
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024161
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024176
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025557
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029778
,D/CheckinService( 2181): Recording last checkin time for package unspecified as 1452763968827
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360063629
,D/PMS     (  910): releaseWL(42630fd0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  910): acquireWL(431ddf90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{424d1988: PendingIntentRecord{424d1c18 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141364, Int=0
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
,D/PMS     (  910): acquireWL(42601dd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =9409 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/PMS     (  910): releaseWL(431ddf90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=238
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  910): acquireWL(43142278): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4049 10111 null
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1277): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/Launcher( 1277): Deferring update until onResume
,D/Launcher( 1277): waitUntilResume // bindAppsUpdated
,W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,W/SystemReader( 1261): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
D/PMS     (  910): releaseWL(43142278): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  910): Resuming delayed broadcast
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/IcingCorporaProvider( 2838): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  910): acquireWL(43460918): PARTIAL_WAKE_LOCK  AsyncService 0x1 4109 10160 null
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(4352ab98): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 15.312MB for 1821008-byte allocation
D/PMS     (  910): releaseWL(43460918): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 17.049MB for 1821008-byte allocation
,D/PMS     (  910): releaseWL(4352ab98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43759b40): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  910): releaseWL(43759b40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(441a5598): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2181): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2181): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2181): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  910): Unable to load service info ResolveInfo{43c51e78 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1228): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/IcingCorporaProvider( 2838): UpdateCorporaTask done [took 588 ms] updated apps [took 588 ms] 
I/ActivityManager(  910): Resuming delayed broadcast
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(43793628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43793628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(4267b460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4267b460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43c79d78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43c79d78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42601dd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b9dbd0 +
,I/Prism.WidgetManager( 1277): onLoadItems() +
,I/Icing   ( 2181): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2181): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(441a5598): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1277): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1277): onLoadItems() -
,I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b9dbd0 -
,D/PhoneApp( 1248): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1248): -- N1 =0
,D/PhoneApp( 1248): -- N2 =0
,D/PhoneApp( 1248): -- N3 =0
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  910): acquireWL(4419acb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f44698: PendingIntentRecord{420264b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149734, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4419acb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44034780 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(4365bdb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(4365bdb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1532): service - handleMessage() stop self
,D/AutoSetting( 1532): service - onDestroy() END
,D/AutoSetting( 1532): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4508
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4508:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4508
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(43ccb960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{43c73490: PendingIntentRecord{44082460 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=171965, Int=0
,D/PMS     (  910): releaseWL(43ccb960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/ClearcutLoggerApiImpl( 1365): disconnect managed GoogleApiClient
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(43456398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43456398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(436c8d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f44698: PendingIntentRecord{420264b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209733, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(436c8d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(4274a490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4274a490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4266b9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4266b9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(426bc1c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41f44698: PendingIntentRecord{420264b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=269734, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(426bc1c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4261fec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4261fec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4623): --= Surplus to requirements =--
I/jxcore-log( 4623): 
I/jxcore-log( 4623): ****TEST TOOK:  ms ****
I/jxcore-log( 4623): 
,I/jxcore-log( 4623): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4623): 
,E/cutils-trace( 4936): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4936): ====startRecUseTime====
D/htc.customization.log.level( 4936):  is 
,W/CustomizationLogLevel( 4936): Level value is invalid, use default level 2
,D/CustomizationManager( 4936):  Read ACC file spent 0.113 (s)
D/CIDMapFileReader( 4936): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4936): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4936): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4936): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4936): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4936): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4936): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4936): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4936): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4936): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4936): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4936): Parsing tag category name = system
,I/CustomizationCIDLoader( 4936): Parsing tag category name = application
I/CustomizationCIDLoader( 4936): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4936): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4936): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4936): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4936): Parsing tag category name = Settings
D/CustomizationManager( 4936):  Read CID file spent 0.169 (s)
,D/CustomizationManager( 4936):  All configurations done spent 0.169 (s)
,W/HtcNativeFlag( 4936): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4936): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4936): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4936): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4936, uid=2000 user=0
,I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  910): killProcessQuiet, pid=4623
,I/ActivityManager(  910): Killing 4623:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  910):   Force finishing activity ActivityRecord{41db9cb0 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  910): Copying FileAsset 0x6461d188 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1212): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4623 uid 10389
,W/PackageSettings(  910): Skipping PackageSetting{42289ce0 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1228): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): acquireWL(43f4d390): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43f4d390): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,D/VoicemailCleanupService( 1302): Cleaning up data for package: com.test.thalitest
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/SystemReader( 1261): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,W/InputDispatcher(  910): channel '426b52b0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  910): channel '426b52b0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  910): Attempted to unregister already unregistered input channel '426b52b0 com.test.thalitest.MainActivity (s)'
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/Launcher( 1277): Deferring update until onResume
,D/Launcher( 1277): waitUntilResume // bindAppsRemoved
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowManager(  910): WINDOW DIED Window{426b52b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/WifiService(  910): Client connection lost with reason: 4
,W/WindowManager(  910): Failed looking up window
W/WindowManager(  910): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@4244c2e0 does not exist
W/WindowManager(  910): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  910): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  910): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  910): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  910): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  910): WIN DEATH: null
,W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/Prism.PackageStateRece_( 1277): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/IcingCorporaProvider( 2838): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4953 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  910): acquireWL(43bf9188): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43bf9188): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43bd8640): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2838): UpdateCorporaTask done [took 254 ms] updated apps [took 254 ms] 
,E/SQLiteDatabase( 4953): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4953): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734),
E/SQLiteDatabase( 4953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4953): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4953): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4953): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4953): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4953): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4953): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4953): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4953): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4953): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4953): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4953): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4953): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4953): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4953): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4953): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4953): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4953): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4953): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4953): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4953): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4953): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4953): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4953): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4953): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4953): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4953): 	at Bw.a(ClientF,lagsModule.java:32)
E/SQLiteOpenHelper( 4953): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4953): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4953): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4953): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4953): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4953): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4953): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4953): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4953): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4953): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4953): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4953): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4953): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4953): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4953): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4953): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4953): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4953): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4953): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4953): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4953): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4953): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4953): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4953): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4953): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4953): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4953): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4953): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4953): threadid=11: thread exiting with uncaught exception (group=0x416dae30)
,E/AndroidRuntime( 4953): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4953): Process: com.google.android.apps.docs, PID: 4953
E/AndroidRuntime( 4953): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4953): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4953): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4953): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4953): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4953): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4953): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
,E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4971 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4953): killProcess, pid=4953
D/Process ( 4953): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  910): Recipient 4953
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4953) has died.
,W/ContextImpl( 4971): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4984 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4971): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4971): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4971): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4971): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4971): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4971): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4971): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4971): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4971): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4971): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4971): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4971): threadid=10: thread exiting with uncaught exception (group=0x416dae30)
E/AndroidRuntime( 4971): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4971): Process: com.android.keychain, PID: 4971
E/AndroidRuntime( 4971): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4971): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4971): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4971): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4971): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4971): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4971): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4971): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4971): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  910): App crashed! Process: com.android.keychain
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
,D/AppTag  ( 4984): getInstance(Context context)
,D/Process ( 4971): killProcess, pid=4971
,D/Process ( 4971): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452764158819.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  910): Recipient 4971
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Process com.android.keychain (pid 4971) has died.
,D/AppTag  ( 4984): getInstance(Context context)
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/AppTag  ( 4984): onCreate()
,D/PMS     (  910): acquireWL(422f0040): PARTIAL_WAKE_LOCK  AsyncService 0x1 4109 10160 null
,D/PMS     (  910): releaseWL(422f0040): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4136): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/Process (  910): killProcessQuiet, pid=4015
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4015:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PackageBroadcastService( 2181): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2181): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2181): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2181): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2181): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2181): Module APK com.google.android.play.games already loaded
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/LocationSettingsChecker( 2181): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 2181): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 2181): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2181): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e52ac58
,E/SQLiteDBG( 2181): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cadba28
,E/DriveAsyncService( 2181): disk I/O error (code 3850)
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
,W/dalvikvm( 2181): threadid=43: thread exiting with uncaught exception (group=0x416dae30)
,E/AndroidRuntime( 2181): FATAL EXCEPTION: PlayGamesAsyncThread1
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
,E/ActivityManager(  910): App crashed! Process: com.google.android.gms
,E/SQLiteDatabase( 2181): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
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
,D/Process ( 2181): killProcess, pid=2181
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
,D/Process ( 2181): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  910): Recipient 4015
,I/ActivityManager(  910): Recipient 2181
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Process com.google.android.gms (pid 2181) has died.
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b9dbd0 +
,I/Prism.WidgetManager( 1277): onLoadItems() +
D/PMS     (  910): handleWLDeath(43bd8640): PARTIAL_WAKE_LOCK  Icing 0x1
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20997ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20996ms
,I/ActivityManager(  910): Resuming delayed broadcast
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20992ms
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20991ms
,E/SQLiteLog( 1365): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1365): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x660cca10
,W/dalvikvm( 1365): threadid=1: thread exiting with uncaught exception (group=0x416dae30)
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
,E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 1365): killProcess, pid=1365
,D/Process ( 1365): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5018 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 5018): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5018 dbg=false s=true
,I/DeviceManagement( 5018): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 5018): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/ActivityManager(  910): Recipient 1365
D/WifiService(  910): Client connection lost with reason: 4
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.process.gapps (pid 1365) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30817ms
,I/DeviceManagement( 5018): WorkflowService: Starting workflow service
,I/DeviceManagement( 5018): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b39e80] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5018): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5018): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 5018): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 5018): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5034 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 5018): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 5018): SessionStateController: Checking invariants...

```
