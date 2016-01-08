#### Test 5497026140aeaf4_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  917): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  917): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  917): doBoolean: SignalStrength 97
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  917):    returned true
E/cutils-trace( 4435): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4435): ====startRecUseTime====
D/htc.customization.log.level( 4435):  is 
W/CustomizationLogLevel( 4435): Level value is invalid, use default level 2
D/CustomizationManager( 4435):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4435): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4435): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4435): Parsing tag category name = system
I/CustomizationCIDLoader( 4435): Parsing tag category name = application
I/CustomizationCIDLoader( 4435): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4435): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4435): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4435): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4435): Parsing tag category name = Settings
D/CustomizationManager( 4435):  Read CID file spent 0.104 (s)
D/CustomizationManager( 4435):  All configurations done spent 0.104 (s)
W/HtcNativeFlag( 4435): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4435): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4435): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4435): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  917): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  917): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  917): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  917): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  917): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  917): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  917): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4435
D/PMS     (  917): acquireHCC(423c3bf8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 917 1000 null
D/PMS     (  917): acquireHCC(42c8a248): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 917 1000 null
W/asset   (  917): Copying FileAsset 0x62ce4de0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  917): @test_code: getHtcIntentFlag: 0 obj: 1142072064
D/PMS     (  917): acquireWL(43652bf8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 917 1000 null
I/FeedHostManager( 1280): [onPause]
I/FeedProviderManager( 1280): onPause
I/FeedHostManager( 1280): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420700b0
I/SocialFeedProvider( 1280): +onPause
I/SocialFeedProvider( 1280): -onPause
I/ActivityManager(  917): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4446 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1280): [trimMemory] 20
W/asset   ( 4446): Copying FileAsset 0x5c7b8428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4446): Binding Chromium to main looper Looper (main, tid 1) {41b2b490}
I/LibraryLoader( 4446): Expected native library version number "",actual native library version number ""
I/chromium( 4446): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4446): Initializing chromium process, renderers=0
,D/PMS     (  917): acquireWL(4425b540): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  917): acquireWL(44205f68): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,W/System.err(  917): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  917): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  917): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  917): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  917): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  917): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440e9678:true
,D/PMS     (  917): releaseWL(4425b540): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4446): 1102330976: getState(). Returning 12
,I/Adreno-EGL( 4446): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4446): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4446): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4446): Local Branch: 
I/Adreno-EGL( 4446): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4446): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4446):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4446): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4446): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4446): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4446): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4446): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4446): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4446): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,W/dalvikvm( 4446): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4446): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4446): CordovaWebView is running on device made by: HTC
,W/AwContents( 4446): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  917): Disable input method client, pid=1280
,W/ResourceType( 4446): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4446): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b75310, mServedView=org.apache.cordova.engine.SystemWebView{41b3af78 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  917): Enable input method client, pid=4446
W/XT9_C   ( 1215): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1215): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1215): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1215): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4446): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  917): Displayed com.test.thalitest/.MainActivity: +410ms
,D/PMS     (  917): releaseWL(43652bf8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4446): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4446): JniHelper::setJavaVM(0x41605048), pthread_self() = 1662875168
,D/JX-Cordova( 4446): jxcore cordova android initializing
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 11.538MB for 63974-byte allocation
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 11.587MB for 95956-byte allocation
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 11.666MB for 143930-byte allocation
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 11.782MB for 215890-byte allocation
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 11.957MB for 323830-byte allocation
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 12.632MB for 728606-byte allocation
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 13.229MB for 1092904-byte allocation
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 14.103MB for 1639352-byte allocation
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 15.453MB for 2459024-byte allocation
,W/CpuWake (  917): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  917): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  917): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  917): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  917): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  917): <<release mCpuPerf_Freq wakelock
D/PMS     (  917): releaseHCC(423c3bf8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  917): releaseHCC(42c8a248): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4446): Grow heap (frag case) to 17.446MB for 3688532-byte allocation
,D/WIFI_ICON( 1123): WifiActivity: 0
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 4446): Initializing JXcore engine
,W/jxcore-log( 4446): JXcore engine is ready
,W/jxcore-log( 4446): Starting JXcore engine
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  917): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  917): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  917): doBoolean: SignalStrength 97
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  917):    returned true
,W/jxcore-log( 4446): Platform android
W/jxcore-log( 4446): 
,W/jxcore-log( 4446): Process ARCH arm
W/jxcore-log( 4446): 
,I/PMS     (  917): Going to sleep due to screen timeout...
,I/SensorManager(  917): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422581e8
W/SensorService(  917): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  917): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  917): pid=917, uid=1000
I/ActivityManager(  917): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  917): Couldn't get kernel wake lock stats
V/LightsService(  917): setLight #2: color=#0
D/qdlights(  917): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  917): setLight #0: color=#0
W/SensorService(  917): Active sensors: size = 2
W/SensorService(  917): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  917): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  917): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422581e8, eanble = 0, strlen(mName) = 59
W/SensorService(  917): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  917): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42016300
W/SensorService(  917): Listener[1] = com.htc.smartdim.sensor_eye@42763990
W/SensorService(  917): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  917): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  917): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  917): mWirelessDisplayManager is null
,I/jxcore-log( 4446): JXcore Cordova bridge is ready!
I/jxcore-log( 4446): 
,W/jxcore-log( 4446): JXcore engine is started
,I/chromium( 4446): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4446): Skipped 143 frames!  The application may be doing too much work on its main thread.
D/WIFI_ICON( 1123): WifiActivity: 1
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4446): Toggling radios to true
I/jxcore-log( 4446): 
,D/BluetoothAdapter( 4446): enable(): BT is already enabled..!
,D/WifiManager( 4446): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  917): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  917): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  917): Settings:Agentvalue: 2
W/Settings:Agent(  917): >> traceCallingStack()
W/Settings:Agent(  917): Process.myPid(): 917
W/Settings:Agent(  917): Process.myTid(): 1364
W/Settings:Agent(  917): Process.myUid(): 1000
W/Settings:Agent(  917): 
W/Settings:Agent(  917): 
W/System.err(  917): java.lang.Throwable: stack dump
W/System.err(  917): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  917): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  917): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  917): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  917): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  917): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  917): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
D/WifiService(  917): New client listening to asynchronous messages
D/WifiService(  917): setWifiEnabled: true pid=4446, uid=10389
E/WifiService(  917): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  917): isSprintWifiRestricted(): false
I/WifiService(  917): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  917): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  917): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  917): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  917): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  917): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  917): 
W/Settings:Agent(  917): << traceCallingStack(): 4(ms)
D/WifiManager( 4446): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  917): doBoolean: DISCONNECT
D/WifiManager( 4446): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): TDLS: Tear down peers
I/wpa_supplicant( 1165): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4446): Radios toggled
I/jxcore-log( 4446): 
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1165): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1165): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1165): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  917): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/HTCRequest(  917): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  917): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb6fd6bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1165):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1165): State: COMPLETED -> DISCONNECTED
D/HTCRequest(  917): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  917): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  917): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  917): WifiMonitor:getReasonFromEventString() 3
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/HTCRequest(  917): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1165): State: DISCONNECTED -> DISCONNECTED
D/wpa_,supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  917): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/HTCRequest(  917): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  917): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1165): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1165): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  917):    returned true
,D/WifiPerfLock(  917): release()
D/WifiStateMachine(  917): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  917): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  917): interfaceLinkStateChanged wlan0, false
,D/Tethering(  917): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
D/Tethering(  917): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  917): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  917): acquireWL(423de3b0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 917 1000 null
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/Tethering(  917): interfaceLinkStateChanged wlan0, false
D/Tethering(  917): interfaceStatusChanged wlan0, false
D/HTCRequest(  917): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  917): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  917):    returned true
D/Tethering(  917): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  917): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/SurfaceControl(  917): Excessive delay in blankDisplay() while turning screen off: 316ms
D/PMS     (  917): releaseWL(44205f68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/WifiP2pService(  917): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  917): nativeSetInteractive:false
D/PMS     (  917): nativeSetInteractive:false done
D/PMS     (  917): nativeSetAutoSuspend:true
D/PMS     (  917): nativeSetAutoSuspend:true done
D/HABCtrl (  917): TPE algorithm. remove timeout.
D/WifiP2pService(  917): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  917): OOBE c monitor 11
I/InputManager(  917): Cancel all due to getting PMS screen off broadcast
,D/WifiNative-wlan0(  917):    returned true
,D/NfcService( 1262): ScreenObserver: OFF
D/NfcService( 1262): applyRouting - 0
,I/IntentController( 1123): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  917): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  917): Disable input method client, pid=4446
D/libc    (  917): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  917): [NET] getaddrinfo-, SUCCESS
D/NfcService( 1262): applyRouting -2
,D/WifiStateMachine(  917): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/KeyguardServiceDelegate(  917): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42a1a218)
,D/WifiNative-wlan0(  917): doBoolean: RECONNECT
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): Fast associate: Old scan results
I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): State: DISCONNECTED -> SCANNING
D/libc    (  917): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/PMS     (  917): acquireWL(42337168): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
D/PMN     (  917): wakingUp
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
D/libc    (  917): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  917): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiMonitor(  917): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  917):    returned true
D/WifiStateMachine(  917): Enter handleNetworkDisconnect
,D/DhcpStateMachine(  917): [RunningState] Stop DHCP
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  917): doBoolean: DRIVER POWERMODE 0
V/KeyguardServiceDelegate(  917): **** SHOWN CALLED ****
,D/WifiDataStallTracker(  917): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  917): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/PMS     (  917): releaseWL(42337168): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/WindowManager(  917): No lock screen! windowToken=null
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
D/WifiDataStallTracker(  917): stopDataStallAlarm: current tag=20196 mDataStallAlarmIntent=PendingIntent{440a21a8: PendingIntentRecord{42026e90 android broadcastIntent}}
D/WifiNative-wlan0(  917):    returned true
,D/WifiNative-wlan0(  917): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  917):    returned true
D/WifiP2pService(  917): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  917): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  917): acquireWL(41ff82e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  917): n_update end
D/PMS     (  917): releaseWL(41ff82e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/PMN     (  917): onScreenOn
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
D/UsbnetStateTracker(  917): isAvailable+-
D/UsbnetStateTracker(  917): reconnect
,D/UsbnetStateTracker(  917): isAvailable+-
,D/WifiStateMachine(  917): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4100): >>>>>WISPrService start isConnected = false<<<<<
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
D/WifiStateTracker(  917): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  917): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  917): Provision feature enable=false
D/ConnectivityService(  917): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/ConnectivityService(  917): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  917): default: reconnect()
D/MDST    (  917): default: setTeardownRequested(false)
D/MDST    (  917): default: setEnableApn apnType =default , enable=true
D/WifiStateMachine(  917): Exit handleNetworkDisconnect
D/NfcService( 1262): applyRouting - 0
D/WifiStateMachine(  917): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  917): [MLHD] enter handleMediaLinkEvent DefaultState
D/AutoSetting( 1349): receiver - intent: android.intent.action.USER_PRESENT
,D/MtpService( 2372): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WISPrService( 4100): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  917): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  917): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/HtcPowerSaver(  917): updateBatteryInfo
D/PMS     (  917): acquireWL(4247eee0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
D/ConnectivityService(  917): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  917): New client listening to asynchronous messages
D/MtpService( 2372): [MTP][onReceive]-
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NfcService( 1262): applyRouting -2
D/DotMatrix( 1596): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/ClockThread( 1123): stop update clock
W/ConnectivityService(  917): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  917): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/AlarmManager(  917): ACTION_SCREEN_ON
I/AlarmManager(  917): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  917): [AlarmQueuing] done recovering
D/ConnectivityService(  917): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
I/AlarmManager(  917): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  917): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  917): releaseWL(4247eee0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/ConnectivityService(  917): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  917): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NativeCrypto( 1375): Read error: ssl=0x663176e0: I/O error during system call, Connection timed out
,D/WISPrService( 4100): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4100): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  917): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiStateMachine(  917): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,V/NativeCrypto( 1375): SSL shutdown failed: ssl=0x663176e0: I/O error during system call, Broken pipe
,D/AutoSetting( 1349): service - onCreate()
W/ConnectivityService(  917): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  917): handleConnectivityChange: resetting
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  917): resetConnections(wlan0, 3)
D/PMS     (  917): acquireWL(4353c8c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
D/WirelessDisplayService(  917): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  917): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  917): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/libc    (  363): [NET] entry_id:3   entry:0xb8293db8  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8293c88  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8293f70  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb828ac20  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb828f458  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb828f2d8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,D/AutoSetting( 1349): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  917): flush DNS cache for net 1(wlan0)
,V/NotificationService(  917): batLight: Full, plugged
,V/LightsService(  917): setLight #8: color=#c8c800
,D/qdlights(  917): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/Nat464Xlat(  917): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/Nat464Xlat(  917): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/qdlights(  917): [LedInfo] has indicator attribute mode=x0ff
,V/LightsService(  917): setLight #8: color=#c800
D/qdlights(  917): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  917): [LedInfo] has indicator attribute
D/qdlights(  917): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  917): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  917): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  917): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  917): BroadcastReceiver::onReceive+
D/UsbnetService(  917): onReceive BATTERY_CHANGED
D/UsbnetService(  917):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  917): BroadcastReceiver::onReceive-
,D/AutoSetting( 1349): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/qdlights(  917): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  917): runPSCheck
D/HtcPowerSaver(  917): Checking...
I/HtcPowerSaver(  917): >> updateStatus
D/ConnectivityService(  917): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  917): acquireWL(4269b6a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 917 1000 null
D/WifiDataStallTracker(  917): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  917): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  917): onReceive: action=android.intent.action.SCREEN_ON
,D/LocationManagerService(  917): request 42649e90 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  917): provider request: passive ProviderRequest[ON interval=0]
D/TetherSettings( 4100): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4100): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4100): Cust_ConnectToPC   : Modem_Link>false
D/WirelessDisplayService(  917): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  917): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/        ( 4100): Cust_ConnectToPC   : spcsc>false
D/        ( 4100): Cust_ConnectToPC   : IPT>true
D/WifiNative-wlan0(  917): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  917): doBoolean: SET pno 0
,D/        ( 4100): Cust_ConnectToPC   : Singel_USB>false
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
,D/WifiStateMachine(  917): startScan Pid: 917 Uid 1000
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:On
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  917):    returned true
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
I/HtcPowerSaver(  917): updateStatus (8000,100,-1,false,false,false,-1)
D/ConnectivityService(  917): reportInetCondition for net -1, percentage: 0 by  (1375/10029)
I/HtcPowerSaver(  917): << updateStatus
D/WifiStateTracker(  917): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/ConnectivityService(  917): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  917): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  917): getNetworkInfo networkType=1 called by  (917/1000)
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 1165): wpa_supplicant_scan enter
W/Settings( 4100): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  917):    returned true
D/WifiNative-wlan0(  917): doBoolean: SCAN
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
I//system/bin/ip(  363): RTNETLINK answers: No such process
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
E/SmartNS_Utility( 4100): hasRemovableStorageSlot: true
D/WifiNative-wlan0(  917):    returned false
D/SmartNS_Utility( 4100): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4100): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:0
,V/SRS_Proc(  370): ParamSet string: screen_state=on
D/BatSI   (  917): WIFI scan started for: 450a0300 uid:1000
V/NotificationService(  917): batLight: Full, plugged
V/LightsService(  917): setLight #8: color=#c8c800
D/qdlights(  917): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  917): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  917): setLight #8: color=#c800
D/qdlights(  917): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  917): [LedInfo] has indicator attribute
D/qdlights(  917): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  917): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  917): releaseWL(4353c8c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): releaseWL(4269b6a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/WirelessDisplayService(  917): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/PSReceiver( 4100): onReceive:android.intent.action.USER_PRESENT
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
W/ContextImpl( 4100): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4100): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4100): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/NetworkPolicy(  917): updateScreenOn: false
D/ConnectivityService(  917): mActiveDefaultNetwork: -1
,D/ConnectivityService(  917): handleInetConditionChange: no active default network - ignore
I/SmartNS_PSService( 4100):  defaultType:0
,I/ActivityManager(  917): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4507 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1596): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  917): acquireWL(425b7218): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(425b7218): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(434992b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(434992b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4507): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1778): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): onScreenOn: 1452278304020
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1778): onScreenOn: 1452278304020
,D/SmartSyncUtils( 4507): isEpsOn(), nState = 0
,I/SensorManager(  917): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42016300
D/PMS     (  917): acquireWL(43ee8290): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4507 1000 null
W/SensorService(  917): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  917): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  917): pid=917, uid=1000
W/SensorService(  917): Active sensors: size = 2
W/SensorService(  917): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  917): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  917): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42016300, eanble = 0, strlen(mName) = 91
W/SensorService(  917): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  917): Listener[0] = com.htc.smartdim.sensor_eye@42763990
,W/SensorService(  917): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  917): goingToSleep
D/PMS     (  917): acquireWL(4373d0f0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 917 1000 null
,D/AlarmManager(  917): ACTION_SCREEN_OFF
I/AlarmManager(  917): [AlarmQueuing] screen off now: 
I/AlarmManager(  917): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  917): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  917): stopDataStallAlarm: current tag=20197 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  917): doBoolean: SET pno 1
D/WifiNative-wlan0(  917): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:Off
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1165): get_ip_address source addr = 02000000
I/wpa_supplicant( 1165): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  917):    returned true
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): CTRL_IFACE SET 'pno'='1'
I/AlarmManager(  917): [AlarmQueuing] wifi connection: true
D/PMS     (  917): acquireWL(437afa28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 917 1000 null
,D/PMS     (  917): releaseWL(43ee8290): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4507): getMobilePolicyEnabled, result = true
,D/NetworkPolicy(  917): updateScreenOn: false
D/ContactMessageStore( 1246): start background delete task...
D/ContactMessageStore( 1246): size: 0 , 0
,D/ContactMessageStore( 1246): Background delete complete
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1165): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1165): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 3
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 1
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): selected network = 1
D/wpa_supplicant( 1165): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb6fd84e8  current_ssid=0x0
D/wpa_supplicant( 1165): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1165): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1165): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1165): check if in concurrent case
,I/wpa_supplicant( 1165): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiNative-wlan0(  917):    returned true
D/wpa_supplicant( 1165): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1165): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1165): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1165): RSN: PMKSA cache search - network_ctx=0xb6fd84e8 try_opportunistic=0
D/wpa_supplicant( 1165): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1165): RSN: No PMKSA cache entry found
,W/ContextImpl(  917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/wpa_supplicant( 1165): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1165): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1165): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1165): nl80211: Unsubscribe mgmt frames handle 0xb6fd7718 (mode change)
D/wpa_supplicant( 1165): nl80211: Subscribe to mgmt frames with non-AP handle 0xb6fd7718
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb6fd7718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1165):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1165):   * freq=2412
D/wpa_supplicant( 1165):   * Auth Type 0
D/wpa_supplicant( 1165):   * WPA Versions 0x2
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1165): nl80211: Connect request send successfully
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  917): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/WifiMonitor(  917): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  917): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMOD,E 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  917):    returned true
D/WifiNative-wlan0(  917): doBoolean: SET pno 1
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  917):    returned true
D/WifiStateMachine(  917): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  917): doString: LIST_DONGLES
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  917): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (376) for get BSS: id=0
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-48
I/wpa_supplicant( 1165): tsf=0000000022120232
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=1
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-56
I/wpa_supplicant( 1165): tsf=0000000102596768
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=2
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-81
I/wpa_supplicant( 1165): tsf=0000000022120249
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
D/PMS     (  917): releaseWL(437afa28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  917): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  917): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 22120232, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  917): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 102596768, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  917): getDiscoveryDongleList
D/WifiStateMachine(  917): == begin of scan result ==
D/WifiStateMachine(  917): == (3) end of scan result ==
D/WirelessDisplayService(  917): getDiscoveryDongleList
D/WifiManager( 1228): getScanResults enter 
D/WifiStateMachine(  917): == begin of scan result ==
D/WifiStateMachine(  917): == (3) end of scan result ==
D/WifiStateMachine(  917): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 22120249, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  917): add 3 to mScanResults
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/BatSI   (  917): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  917): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
W/ContextImpl( 4507): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4507): isEpsOn(), nState = 0
D/SmartSyncUtils( 4507): isEpsOn(), nState = 0
D/SmartSyncUtils( 4507): getMobilePolicyEnabled, result = true
D/WifiService(  917): New client listening to asynchronous messages
I/SensorManager(  917): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42763990
W/SensorService(  917): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  917): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  917): pid=917, uid=1000
W/SensorService(  917): Active sensors: size = 1
W/SensorService(  917): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  917): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42763990, eanble = 0, strlen(mName) = 36
W/SensorService(  917): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  917): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  917): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  917): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  917): pid=917, uid=1000
W/SensorService(  917): Active sensors: size = 0
W/SensorService(  917): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42763990, eanble = 0, strlen(mName) = 36
W/SensorService(  917): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  917): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  917): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42763990
W/ContextImpl(  917): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  917): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42763dd0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  917): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42763dd0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  917): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  917): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  917): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  917): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  917): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  917): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  917): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  917): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  917): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  917): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  917): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  917): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  917): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  917): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  917): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  917): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  917): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  917): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  917): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  917): 	at dalvik.system.NativeStart.main(Native Method)
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1596): [EventService] getTotalRam: 1873 Mb
D/PMS     (  917): acquireWL(44146a20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): releaseWL(44146a20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): acquireWL(43833768): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): releaseWL(43833768): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1778): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1778): onScreenOff
D/AutoSetting( 1349): service - mHandler: cancel location update
,D/AutoSetting( 1349): service -           changes count: 0
,D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1165): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Connect event
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1165): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1165): Add randomness: count=7 entropy=1
I/wpa_supplicant( 1165): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1165): TDLS: Remove peers on association
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  917): interfaceLinkStateChanged wlan0, false
D/Tethering(  917): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1165): EAPOL: enable timer tick
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1165): getPrivFuncNum +	
D/Tethering(  917): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  917): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1165): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1165): Get randomness: len=32 entropy=2
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  917): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  917): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  917): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  917): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  917): interfaceLinkStateChanged wlan0, true
D/Tethering(  917): interfaceStatusChanged wlan0, true
,D/Tethering(  917): [isWifi] getHotspotEnabled: false
,D/HTCRequest(  917): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  917): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  917): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  917): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  917): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  917): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  917): Enter handleAssociatedWithEvent
D/WifiStateMachine(  917): Associated
D/WifiStateMachine(  917): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  917): Exit handleAssociatedWithEvent
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  917): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  917): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  917): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  917): updateConnectedAP...
I/wpa_supplicant( 1165): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fd79f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1165):    addr=c0:ff:d4:d3:aa:48
,D/WifiApDatabaseHandler(  917): updateConnectedAP...
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 10
D/WifiStateMachine(  917): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1165): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6efeb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1165):    broadcast key
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  917): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1165): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1165): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  917): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1165): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  917): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  917): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  917): This record is existed, only update it...
D/WifiStateMachine(  917): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1165): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=6
D/WifiApDatabaseHandler(  917): updateConnectedAP...
I/wpa_supplicant( 1165): set send_ind_to_ndc = 0
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (1)+
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  917): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1165): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  917): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1165): EAPOL authentication completed successfully
I/wpa_supplicant( 1165): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
,D/Tethering(  917): interfaceLinkStateChanged wlan0, true
,D/Tethering(  917): interfaceStatusChanged wlan0, true
,D/Tethering(  917): [isWifi] getHotspotEnabled: false,
,D/WifiStateMachine(  917): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  917): updateConnectedAP...,
,D/WifiStateMachine(  917): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  917): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  917): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  917): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  917): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  917): This record is existed, only update it...
D/WifiStateMachine(  917): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  917): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  917): updateConnectedAP...
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  917): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateTracker(  917): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  917): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  917): Provision feature enable=false
D/ConnectivityService(  917): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiApDatabaseHandler(  917): updateConnectedAP...
D/WISPrService( 4100): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4100): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiNative-wlan0(  917): doBoolean: SET pno 0
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1165): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  917):    returned true
D/DhcpStateMachine(  917): [StoppedState] Start DHCP
D/WifiStateMachine(  917): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  917): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  917):    returned true
D/WifiNative-wlan0(  917): doBoolean: DRIVER SETSUSPENDMODE 0
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16,
D/WifiNative-wlan0(  917):    returned true
D/WifiNative-wlan0(  917): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 1
,I/wpa_supplicant( 1165): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  917):    returned true,
D/WifiNative-wlan0(  917): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  917):    returned null
E/WifiStateMachine(  917): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  917): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  917):    returned null
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiStateMachine(  917): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  917): acquireWL(434ba9d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 917 1000 null
D/WifiStateMachine(  917): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  917): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41ce73c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  917): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41ce73c8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:1
,W/ActivityManager(  917): Activity pause timeout for ActivityRecord{42453360 u0 com.test.thalitest/.MainActivity t2}
,D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  917): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  917): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  917): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4540 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  917): getNetworkInfo networkType=1 called by  (917/1000)
,D/PMS     (  917): acquireWL(43568370): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 917 1000 null
,D/GpsLocationProvider(  917): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  917): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  917): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  917): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  917): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  917): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  917): NoActiveNetworkState
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/PMS     (  917): releaseWL(43568370): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,I/ConnectivityHelper( 1280): [onReceive] WIFI(1): CONNECTING
,D/htcCheckinService(  917): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  917): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/Tethering(  917): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/ConnectivityService(  917): getNetworkInfo networkType=1 called by com.htc.launcher (1280/10076)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.backuptransport (1608/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.docs (4290/10100)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
,V/Tethering(  917): bSetPropertyMultiRAB:false
,D/Tethering(  917): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  917): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  917): ipv4Default null
,I/Tethering(  917): No IPv4 upstream interface, giving up.
,D/Tethering(  917): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.docs (4290/10100)
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
,I/MusicStore( 4540): Database version: 95
,W/ContextImpl( 4540): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4540): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4540, uid=10154, userID:0
,D/WifiDisplayAdapter(  917): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  917):     Client/Owner: Client
D/WifiDisplayAdapter(  917):     GroupId: 
D/WifiDisplayAdapter(  917):     Passphrase: 
D/WifiDisplayAdapter(  917):     SessionId: 0
D/WifiDisplayAdapter(  917):     IP Address: }
,D/MediaRouterService(  917): Client com.google.android.music (pid 4540): Registered
,D/WifiDisplayAdapter(  917): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  917):     Client/Owner: Client
D/WifiDisplayAdapter(  917):     GroupId: 
D/WifiDisplayAdapter(  917):     Passphrase: 
D/WifiDisplayAdapter(  917):     SessionId: 0
D/WifiDisplayAdapter(  917):     IP Address: }
I/MediaRouter( 4540): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.music (4540/10154)
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (2372/10021)
,I/ActivityManager(  917): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4560 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4540): getSelectedRoute
,I/NetworkMonitor( 4540): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  917): getNetworkInfo networkType=1 called by com.google.android.music (4540/10154)
,D/ACRA    ( 4560): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4560): Looking for error files in /data/data/com.facebook.katana/app_acra-reports,
,D/ACRA    ( 4560): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4540, uid=10154, userID:0
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/PMS     (  917): acquireWL(43ccbbd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 917 1000 null
,D/PMS     (  917): releaseWL(43ccbbd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  917): killProcessQuiet, pid=4225
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  917): Killing 4225:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  917): Recipient 4225
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4560): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4560): Preparing secondary program dexes.
V/DexLibLoader( 4560): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4560): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4560): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4560): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4560): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,D/WifiService(  917): Client connection lost with reason: 4
W/DexLibLoader( 4560): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4560): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4560): Dex already copied
D/OdexVerifier( 4560): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4560): Creating class loader
V/DexLibLoader( 4560): Finished creating class loader
V/DexLibLoader( 4560): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4560): Dex already copied
D/OdexVerifier( 4560): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4560): Creating class loader
V/DexLibLoader( 4560): Finished creating class loader
V/DexLibLoader( 4560): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4560): Dex already copied
D/OdexVerifier( 4560): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4560): Creating class loader
V/DexLibLoader( 4560): Finished creating class loader
V/DexLibLoader( 4560): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4560): Dex already copied
D/OdexVerifier( 4560): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4560): Creating class loader
V/DexLibLoader( 4560): Finished creating class loader
V/DexLibLoader( 4560): Verifying classes from secondary dexes.
D/DexLibLoader( 4560): DexLibLoader.ensureDexLoaded took 19 ms
,D/wpa_supplicant( 1165): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1165): EAPOL: disable timer tick
,W/dalvikvm( 4560): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4560): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4560): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4560): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4560): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4560): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4560): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  917): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  917): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  917): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  917): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  917): [NET] getaddrinfo-, SUCCESS
,D/libc    (  917): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  917): [NET] getaddrinfo-, SUCCESS
D/libc    (  917): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  917): [NET] getaddrinfo-, SUCCESS
D/libc    (  917): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  917): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  917): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  917):    returned true
,D/WifiNative-wlan0(  917): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  917):    returned true
,D/WifiNative-wlan0(  917): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  917):    returned true
D/WifiStateMachine(  917): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  917): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  917): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  917): releaseWL(434ba9d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=66 [3][2][0]
D/WifiStateMachine(  917): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  917): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  917): doBoolean: SignalStrength 97
D/WIFI_ICON( 1123): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  917):    returned true
D/WifiStateMachine(  917): gateway: /192.168.1.1
D/WifiNative-wlan0(  917): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1165): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  917):    returned true
D/WifiStateMachine(  917): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  917): VerifyingLinkState enter
D/WifiStateMachine(  917): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  917): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  917): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  917): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  917): onReceive: action=android.net.wifi.STATE_CHANGE
,V/NetworkPolicy(  917): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  917): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  917): WAN detection
D/WifiStateTracker(  917): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  917): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  917): Provision feature enable=false
D/ConnectivityService(  917): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  917): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  917): default: teardown()
D/MDST    (  917): default: setTeardownRequested(true)
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  917): default: setEnableApn apnType =default , enable=false
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  917): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  917): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4100): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1165): Change stage from stage0 to stage3
,D/WifiStateMachine(  917): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/MDST    (  917): default: setTeardownRequested(true)
D/ConnectivityService(  917): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  917): Unexpected mtu value: android.net.wifi.WifiStateTracker@424bf4d8
D/ConnectivityService(  917): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/WifiStateMachine(  917): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  917): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  917): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  917): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  917): handleConnectivityChange: resetting
D/Nat464Xlat(  917): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  917): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,D/WirelessDisplayService(  917): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  917):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  917): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  917): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  917): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  917): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  917): acquireWL(43794ca0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 917 1000 null
,D/ConnectivityService(  917): getNetworkInfo networkType=1 called by  (917/1000)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1123): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  917): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  917): releaseWL(43794ca0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/dalvikvm( 4560): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4560): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4560): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4560): Verify
,D/WifiService(  917): New client listening to asynchronous messages
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4560): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4560): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  917): killProcessQuiet, pid=3800
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  917): Killing 3800:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  917): Recipient 3800
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1349): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  917): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4611 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1349): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1349): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1349): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1349): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  917): getActiveNetworkInfo called by com.htc.sense.hsp (1349/10055)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.htc.sense.hsp (1349/10055)
,W/fb4a(:<default>):UserScope( 4560): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4611): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4611): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4611): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4611): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4560): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4560): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  917): killProcessQuiet, pid=4038
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  917): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4625 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  917): Killing 4038:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.setupwizard (4611/10079)
,D/PMS     (  917): acquireWL(42604018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.setupwizard (4611/10079)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.setupwizard (4611/10079)
,D/PMS     (  917): acquireWL(4272a500): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2191): Checkin interval check for package: unspecified last checkin: 1452278253911 min interval config: 0 actual interval: 52806
D/PMS     (  917): releaseWL(42604018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2191): Checking schedule, now: 1452278306722 next: 1452278283873
,I/CheckinService( 2191): active receiver: enabled
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2191, uid=10029, userID:0
,I/CheckinService( 2191): Preparing to send checkin request
,I/EventLogService( 2191): Accumulating logs since 1452278250661
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
,I/ActivityManager(  917): Recipient 4038,
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  917): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4641 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  917): killProcessQuiet, pid=4259
,I/ActivityManager(  917): Killing 4259:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  917): Recipient 4259
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CheckinRequestBuilder( 2191): Checkin reason type: 8 attempt count: 1
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 9.960MB for 84664-byte allocation
I/ActivityManager(  917): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 2191): Failed to find provider info for com.google.android.wearable.settings
E/dalvikvm( 4560): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4560): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4560): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4560): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4560): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4560): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4560): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4560): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4560): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4560): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4560): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4560): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4560): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4560): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4560): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4560): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4560): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4560): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4641): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4641): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4641): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4641): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4641): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 9.981MB for 28144-byte allocation
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 10.019MB for 39954-byte allocation
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 10.096MB for 79892-byte allocation
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  917): getNetworkInfo networkType=9 called by com.google.android.gms (2191/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  917): releaseWL(423de3b0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  917): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.magazines (4641/10151)
,V/WebViewChromiumFactoryProvider( 4641): Binding Chromium to main looper Looper (main, tid 1) {41b34208}
,I/LibraryLoader( 4641): Expected native library version number "",actual native library version number ""
,I/chromium( 4641): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4641): Initializing chromium process, renderers=0
,V/Tethering(  917): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  917): [AlarmQueuing] connectivity wifi: true
D/PMS     (  917): acquireWL(43e8f7f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/CaptivePortalTracker(  917): NoActiveNetworkState
,E/AudioManagerAndroid( 4641): BLUETOOTH permission is missing!
D/PMS     (  917): acquireWL(43d42428): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  917): releaseWL(43e8f7f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.setupwizard (4611/10079)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/ConnectivityService(  917): getNetworkInfo networkType=1 called by  (917/1000)
D/PMS     (  917): acquireWL(43cb8f60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 917 1000 null
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.docs (4290/10100)
,D/CaptivePortalTracker(  917): DelayedCaptiveCheckState
,V/Tethering(  917): bSetPropertyMultiRAB:false
,I/NetworkMonitor( 4540): type=WIFI subType= reason=null isConnected=true
,D/Tethering(  917): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  917): acquireWL(43c25138): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 917 1000 null
D/ConnectivityService(  917): getNetworkInfo networkType=1 called by com.google.android.music (4540/10154)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.htc.musicenhancer (3880/10053)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
D/ConnectivityService(  917): getNetworkInfo networkType=1 called by com.htc.launcher (1280/10076)
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
I/ConnectivityHelper( 1280): [onReceive] WIFI(1): CONNECTED
,I/Tethering(  917): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  917): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/htcCheckinService(  917): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  917): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/Tethering(  917): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  917): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  917): Found interface wlan0
D/Tethering(  917): TetherMasterSM: InitialState processMessage what=3
,D/GpsLocationProvider(  917): [handleMessage] UPDATE_NETWORK_STATE
,I/Adreno-EGL( 4641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4641): Local Branch: 
I/Adreno-EGL( 4641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4641):                  aa63bbd948f41d15fc72f585e
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.backuptransport (1608/10029)
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
D/PMS     (  917): releaseWL(43c25138): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.backuptransport (1608/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.docs (4290/10100)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
D/GpsLocationProvider(  917): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  917): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  917): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  917): releaseWL(43cb8f60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
I/ActivityManager(  917): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4675 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/NSApplication( 4641): Starting up...
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 10.283MB for 75760-byte allocation
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.magazines (4641/10151)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.magazines (4641/10151)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,W/BroadcastQueue(  917): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437b5018 u0 ReceiverList{43913c80 4560 com.facebook.katana/10027/u0 remote:43bb2980}}
,W/BroadcastQueue(  917): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437b5018 u0 ReceiverList{43913c80 4560 com.facebook.katana/10027/u0 remote:43bb2980}}
,W/BroadcastQueue(  917): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4361d618 u0 ReceiverList{43931d58 4560 com.facebook.katana/10027/u0 remote:43960990}}
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/Process (  917): killProcessQuiet, pid=4290
,W/dalvikvm( 4675): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.plus (4083/10160)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.plus (4083/10160)
,I/ActivityManager(  917): Killing 4290:com.google.android.apps.docs/u0a100 (adj 15): empty #17
W/dalvikvm( 4675): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4675): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4675): install
I/MultiDex( 4675): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4675): loading existing secondary dex files
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
,I/MultiDex( 4675): load found 3 secondary dex files
,I/MultiDex( 4675): install done
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (2372/10021)
W/dalvikvm( 4675): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4675): VFY: unable to resolve instance field 36
W/dalvikvm( 4675): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
V/JNIHelp ( 4675): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  917): Recipient 4290
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  917): acquireWL(4350b770): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(4350b770): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1349): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4611): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4611): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.htc.sense.hsp (1349/10055)
D/AutoSetting( 1349): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1349): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  917): getActiveNetworkInfo called by com.htc.sense.hsp (1349/10055)
,D/AutoSetting( 1349): Util - check NLP state, Allowned:false, Enabled:false
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.magazines (4641/10151)
D/AutoSetting( 1349): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.plus (4083/10160)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.apps.plus (4083/10160)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4560): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2191): Checkin interval check for package: unspecified last checkin: 1452278253911 min interval config: 0 actual interval: 53308
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4560): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/PMS     (  917): acquireWL(43963e50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): releaseWL(43963e50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/dalvikvm-heap( 4083): Grow heap (frag case) to 13.509MB for 1821008-byte allocation
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4560): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2191, uid=10029, userID:0
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,I/ProviderInstaller( 4675): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
W/dalvikvm( 4675): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
W/dalvikvm( 4675): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WearableService( 1228): callingUid 10029, callindPid: 1228
,W/dalvikvm( 4675): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4675): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4675): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4675): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4675): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/LocationInitializer( 2191): Restart initialization of location
,E/MDM     ( 1228): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1228): No location to return for getLastLocation()
,W/FusedLocationProvider( 1228): location=null
D/PMS     (  917): acquireWL(4392b018): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): releaseWL(4392b018): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,D/AuthorizationBluetoothService( 1375): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1375): Proximity feature is not enabled.
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4675): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=3598268069
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/Adreno-EGL( 4675): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4675): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4675): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4675): Local Branch: 
I/Adreno-EGL( 4675): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4675): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4675):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4675): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4675): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4675): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4675): Local Branch: 
I/Adreno-EGL( 4675): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4675): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4675):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  370): CdmEngine::OpenSession
I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2600863704
,I/WVCdm   (  370): CdmEngine::CloseSession
,W/Settings( 4675): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4675): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4675): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4675): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4675): Local Branch: 
I/Adreno-EGL( 4675): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4675): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4675):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (4675/10029)
,I/CheckinRequestBuilder( 2191): Classify the device as Phone.
,D/libc    ( 2191): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2191): [NET] getaddrinfo-,err=8
D/libc    ( 2191): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2191): [NET] getaddrinfo-, 1
,D/libc    ( 2191): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =97f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/WifiStateMachine(  917): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  917): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  917): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  917): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 269
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2191): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2191): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2191): [NET] getaddrinfo-,err=8
,D/libc    ( 2191): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2191): [NET] getaddrinfo-,err=8
,D/libc    ( 2191): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2191): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2191): Sending checkin request (12210 bytes)
,D/libc    (  917): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  917): [NET] getaddrinfo-,err=8
D/libc    (  917): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  917): [NET] getaddrinfo-, 1
,D/libc    (  917): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4727 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  917): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  917): Find DNS Address www.htc.com/104.81.130.175,
,W/ActivityManager(  917): Sleep timeout!  Sleeping now.
,D/PMS     (  917): releaseWL(4373d0f0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/CheckinRequestBuilder( 2191): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  917): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2191): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  917): getNetworkInfo networkType=9 called by com.google.android.gms (2191/10029)
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=8 [24][2][0]
,I/CheckinRequestBuilder( 2191): Classify the device as Phone.
,I/CheckinTask( 2191): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2191): Checking schedule, now: 1452278309282 next: 1452801246278
,I/CheckinService( 2191): active receiver: disabled
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2191, uid=10029, userID:0
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,I/CheckinService( 2191): Checking schedule, now: 1452278309326 next: 1452801246278
,I/CheckinService( 2191): active receiver: disabled
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2191, uid=10029, userID:0
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
D/CheckinService( 2191): Recording last checkin time for package unspecified as 1452278309332
D/PMS     (  917): releaseWL(4272a500): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (2191/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/PMS     (  917): acquireWL(43374af8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1375): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1375): [NET] getaddrinfo-,err=8
D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1375): [NET] getaddrinfo-, 1
,D/libc    ( 1375): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b0e0 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,W/fb4a(:<default>):UserScope( 4560): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4560): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 256
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1375): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1375): [NET] getaddrinfo-,err=8
,D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1375): [NET] getaddrinfo-,err=8
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4560): Called registerBroadcastReceiver twice.
,D/PMS     (  917): acquireWL(43288cf0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/PMS     (  917): releaseWL(43374af8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  917): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
,D/ConnectivityService(  917): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  917): handleInetConditionChange: starting a change hold
,D/PMS     (  917): releaseWL(43288cf0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(43784e98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  917): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
D/ConnectivityService(  917): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  917): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  917): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
,D/ConnectivityService(  917): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  917): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,D/PMS     (  917): releaseWL(43784e98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.facebook.katana (4560/10027)
,D/PMS     (  917): acquireWL(43938038): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4540 10154 null
,D/PMS     (  917): releaseWL(43d42428): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/ContextImpl( 4540): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4540, uid=10154, userID:0
,I/MusicLeanback( 4540): Conditions not met for autocaching.
,I/MusicLeanback( 4540): Stop autocaching.
D/PMS     (  917): releaseWL(43938038): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4540): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  917): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  917): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [8][0][0]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1525): service - handleMessage() stop self
,D/AutoSetting( 1525): service - onDestroy() END
,D/AutoSetting( 1525): service - handleMessage() quit looper
,D/Process (  917): killProcessQuiet, pid=4313
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  917): Killing 4313:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  917): Recipient 4313
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4641): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4446): Test app app.js loaded
I/jxcore-log( 4446): 
,I/Choreographer( 4446): Skipped 515 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4446): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4446): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b3af78 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4446): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Process (  917): killProcessQuiet, pid=4277
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  917): Killing 4277:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  917): Recipient 4277
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  917): killProcessQuiet, pid=3880
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  917): Killing 3880:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  917): Recipient 3880
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  917): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4739 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "sms"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1280): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "smsto"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  917):   Scheme: "mms"
,I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Launcher( 1280): Deferring update until onResume
,D/Launcher( 1280): waitUntilResume // bindAppsUpdated
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "mmsto"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,D/CaptivePortalTracker(  917): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  917): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  917): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "sms"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "smsto"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "mms"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "mmsto"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,D/PhoneApp( 1246): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4739): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4739): MmsConfig.loadMmsSettings
,W/dalvikvm( 4739): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4739): VFY: unable to resolve instance field 36
,W/dalvikvm( 4739): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4739): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4739, uid=10111, userID:0
,W/Settings( 4739): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  917): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4762 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4739, uid=10111, userID:0,
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4739, uid=10111, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4739, uid=10111, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4739, uid=10111, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4739, uid=10111, userID:0
,D/PMS     (  917): acquireWL(42751928): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4739 10111 null
,I/ActivityManager(  917): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1349): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1349): handle notify Blinkfeed plugin client changed
I/ActivityManager(  917): Resuming delayed broadcast
,I/IcingCorporaProvider( 2824): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  917): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/MessageFrequencyProvider( 4762): onCreate
,D/MmsCustomizationProvider( 4762): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4762): GetPrviateResource
,V/GetPrviateResource( 4762): GetPrviateResource
D/PMS     (  917): acquireWL(42733c20): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): releaseWL(42751928): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  917): killProcessQuiet, pid=4333
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  917): Killing 4333:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ProviderInstaller( 4739): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  917): Recipient 4333
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MmsCustomizationProvider( 4762): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4739): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4739): MmsConfig.loadFromDatabase
,E/Babel   ( 4739): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4739): MmsConfig.loadFromResources
,E/Babel   ( 4739): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4739): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/PMS     (  917): releaseWL(42733c20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/MessageCustFlag( 4762): sense_version=6.0
,D/BTAccessoryUtil( 4762): createReceiver
,D/BTAccessoryUtil( 4762): registerReceiver return intent = null
D/MessageCustFlag( 4762): sku_id=99
,W/SystemReader( 4762): Cannot find message_ambs_application_id, use default value instead
,I/ActivityManager(  917): Resuming delayed broadcast
W/PackageManager(  917): Unable to load service info ResolveInfo{426f40a8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  917): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  917): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  917): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  917): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  917): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  917): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  917): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  917): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  917): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  917): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  917): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  917): 	at dalvik.system.NativeStart.main(Native Method)
D/Messaging( 4762): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4762): networkCode: 
D/MessageCustFlag( 4762): sku_id=99
D/MmsConfig( 4762): SIE smsPri: null
D/MmsConfig( 4762): networkCode: 
,D/HtcTelephonyCapability( 4762): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4762): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4762): getRATByHtcTelephonyCapability:1
W/SystemReader( 4762): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  917): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  917): acquireWL(431d4ee0): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): acquireWL(434f2f68): PARTIAL_WAKE_LOCK  AsyncService 0x1 4083 10160 null
D/PMS     (  917): releaseWL(434f2f68): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/dalvikvm-heap( 4083): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
D/PMS     (  917): releaseWL(431d4ee0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  917): Resuming delayed broadcast
,D/PMS     (  917): acquireWL(42731a58): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  917): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,I/dalvikvm-heap( 4083): Grow heap (frag case) to 16.944MB for 1821008-byte allocation
,D/PMS     (  917): releaseWL(42731a58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  917): Resuming delayed broadcast
,I/ActivityManager(  917): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  917): acquireWL(43195a30): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(43195a30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  917): Resuming delayed broadcast
,D/PMS     (  917): acquireWL(426ce2d0): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  917): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2191): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2191): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2191): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2824): UpdateCorporaTask done [took 828 ms] updated apps [took 828 ms] 
I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1280): loadItems() com.htc.launcher.pageview.WidgetManager@41bc2d50 +
,I/Prism.WidgetManager( 1280): onLoadItems() +
,D/PMS     (  917): releaseWL(426ce2d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  917): Resuming delayed broadcast
,D/PMS     (  917): acquireWL(441c6598): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  917): Waited long enough for: ServiceRecord{43a361f8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,E/Prism.WidgetManager( 1280): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1280): onLoadItems() -
,I/Prism.ItemManager( 1280): loadItems() com.htc.launcher.pageview.WidgetManager@41bc2d50 -
,D/PhoneApp( 1246): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1246): -- N1 =0
,D/PhoneApp( 1246): -- N2 =0
,D/PhoneApp( 1246): -- N3 =0
,D/RemoteDisplayProvider(  917): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  917): start
,I/GCoreNlp( 1228): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  917): applying state to connected service
D/PMS     (  917): acquireWL(43061bc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(43061bc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  917): applying state to connected service
D/PMS     (  917): acquireWL(42647838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): releaseWL(42647838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): acquireWL(424a8f58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): releaseWL(424a8f58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): acquireWL(41f5e898): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): releaseWL(41f5e898): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2191): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2191): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  917): releaseWL(441c6598): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4762): mNeedToUpdateDate2 start
,D/MmsConfig( 4762): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4762): startAsyncQueryReports ---
,D/SettingsManager( 4762): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b402f0
,I/Messaging( 4762): mccmnc> 
D/MmsAsyncWorkHandler( 4762): 
D/MmsAsyncWorkHandler( 4762): HM tk = 20001
,D/ReportIndicatorCache( 4762): MSG_QUERY_REPORTS >>
D/DraftCache( 4762): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4762): [DraftCache/1] refresh
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1246):  phoneType = -1
D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsConfig( 4762): networkCode: 
,D/Messaging( 4762): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1246):  phoneType = -1
,D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4762): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4762): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4762): createReceiver
,D/MessageCustFlag( 4762): sense_version=6.0
,D/Messaging( 4762): mNeedToUpdateDate2: false
,D/Jerry   ( 4762): start to preload cursor >>>>>>>
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/TelephUtils( 1246): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,V/MmsProvider( 1246): Update uri=content://mms, match=0
,D/MmsSmsV2Provider( 1246):  phoneType = -1
,V/MmsProvider( 1246): selection=st=129 AND m_type!=134
,D/Messaging( 4762): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4762): TransactionService is going to be woken up.
,V/TransactionService( 4762): 1-Creating TransactionService
,D/Messaging( 4762): ViewCache CreatePreload
,D/Messaging( 4762): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4762): onStartCommand: 1
,D/MmsSystemEventReceiver( 4762): unRegisterForConnectionStateChanges
V/TransactionService( 4762): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4762): Loading previous transactions.
,D/Cust_MMSMS( 4762): _has_set_default_values_2=true
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1246): device_type: 1
D/TransactionService( 4762): Force set service start id to 1
V/TransactionService( 4762): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4762): unRegisterForConnectionStateChanges
,D/MsgPreferenceUtils( 4762): def_index: 0
,D/TransactionService( 4762): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4762): Destroying TransactionService
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1246):  phoneType = -1
,D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MsgPreferenceUtils( 4762): globalIndex = 1
,V/TransactionService( 4762): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MsgPreferenceUtils( 4762): phone state: true
D/MsgPreferenceUtils( 4762): sd state: false
,D/MsgPreferenceUtils( 4762): vIndex = 0
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1246): sku_id=99
,D/DraftCache( 4762): [DraftCache/475] rebuildCache
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1246):  phoneType = -1
,D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4762): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/Jerry   ( 1246): URI_DRAFT
,D/DraftCache( 4762): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4762): [DraftCache/475] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4762): 
D/MmsAsyncWorkHandler( 4762): HM tk = 20002
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1246): sku_id=99
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1246): sku_id=99
,I/GAV4    ( 4739): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  917): acquireWL(425f9308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 917 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  917): sending alarm PendingIntent{44104b78: PendingIntentRecord{422d3648 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121522, Int=0
,D/PMS     (  917): acquireWL(424dbec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(425f9308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [11][0][0]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  917): acquireWL(4393ed70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(424dbec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(4393ed70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(42aedae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,D/PMS     (  917): releaseWL(42aedae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(44128528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  917): acquireWL(4372e138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(43327dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1228): Vacuum at: now=1452278323221 tag=VacuumService
,D/PMS     (  917): releaseWL(44128528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(4372e138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(43327dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(426f38d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591,
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,D/PMS     (  917): releaseWL(426f38d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(437d0b50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  917): releaseWL(437d0b50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): acquireWL(43ee4ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,D/PMS     (  917): releaseWL(43ee4ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(431a1ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  917): releaseWL(431a1ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  917): acquireWL(4309c868): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  917): acquireWL(434fc748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(434fc748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(43a436b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(4309c868): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(424d2688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,D/PMS     (  917): releaseWL(424d2688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0,
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1228): Scheduling Phenotype for one-off execution 8991 seconds from now (1452278323857)
,D/GetConfigurationSnapshotOperation( 1228): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1228): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1228): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  917): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1228): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1228): [NET] getaddrinfo-, 1
,D/libc    ( 1228): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6af +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 269
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1228): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/LocationManagerService(  917): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  917): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
,W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  917): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  917): releaseWL(43a436b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(44149458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
,W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,D/PMS     (  917): releaseWL(44149458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(424aa410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  917): doString: SIGNAL_POLL
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024405
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024533
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024587
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024591
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024597
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360024604
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025851
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360025876
W/AlarmManager(  917): Converted elapesd time is over 1 year! when = 315360028646
,D/PMS     (  917): releaseWL(424aa410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(4392ca78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  917): BroadcastReceiver::onReceive+
,D/UsbnetService(  917): onReceive BATTERY_CHANGED
D/UsbnetService(  917):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  917): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  917): n_update end
D/PMS     (  917): releaseWL(4392ca78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  917): updateBatteryInfo
D/PMS     (  917): runPSCheck
D/HtcPowerSaver(  917): Checking...
I/HtcPowerSaver(  917): >> updateStatus
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1596): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  917): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  917): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  917): acquireWL(43701e18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 917 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  917): sending alarm PendingIntent{436f8278: PendingIntentRecord{4264d138 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=132684, Int=0
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (1375/10029)
,D/PMS     (  917): releaseWL(43701e18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1349): service - mHandler: update timezone
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  917): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1525): service - onCreate()
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  917): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  917): batLight: Full, plugged
,D/DotMatrix( 1596): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1596): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
V/LightsService(  917): setLight #8: color=#c8c800
D/qdlights(  917): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  917): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  917): setLight #8: color=#c800
D/qdlights(  917): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  917): [LedInfo] has indicator attribute
D/qdlights(  917): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  917): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1525): service - mHandler: update timezone
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1525): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1525): service - showManualTimeZoneSelector() send notification (single)
,I/PhoneStatusBar( 1123): removeNotification.gc:58
D/DotMatrix( 1596): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1596): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1123): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{41bb64e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 1349): service - mHandler: update timezone
,D/AutoSetting( 1349): service - handleMessage() stop self
,D/AutoSetting( 1349): service - handleMessage() quit looper
,D/AutoSetting( 1349): service - onDestroy() END
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  917): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  917): batLight: Full, plugged
V/LightsService(  917): setLight #8: color=#c8c800
D/qdlights(  917): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  917): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  917): setLight #8: color=#c800
D/qdlights(  917): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  917): [LedInfo] has indicator attribute
D/qdlights(  917): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  917): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/DotMatrix( 1596): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1596): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
W/ActivityManager(  917): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1525): service - mHandler: update timezone
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1525): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1525): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1596): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1596): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1123): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{41f04e48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.htc.htclocationservice 3 9 3 11
,D/PMS     (  917): acquireWL(43767c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 917 1000 WorkSource{1000}
,V/AlarmManager(  917): sending alarm PendingIntent{422f1048: PendingIntentRecord{422cb6a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=138537, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  917): releaseWL(43767c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  917): acquireWL(42bfc080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 917 1000 WorkSource{1000}
,V/AlarmManager(  917): sending alarm PendingIntent{42505628: PendingIntentRecord{4249da60 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141727, Int=0
,D/GpsLocationProvider(  917): ALARM_XTRA_TIMEOUT
,D/PMS     (  917): acquireWL(435a2cb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 917 1000 null
D/GpsLocationProvider(  917): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  917): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  917): releaseWL(42bfc080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  917): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  917): [NET] getaddrinfo-,err=8
D/libc    (  917): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  917): [NET] getaddrinfo-, 1
D/libc    (  917): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =379d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  917): [NET] getaddrinfo_proxy-, success
I/global  (  917): call createSocket() return a new socket.
D/libc    (  917): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  917): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  917): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  917): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  917): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  917):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  917): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  917): killProcessQuiet, pid=4364
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  917): Killing 4364:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  917): Recipient 4364
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  917): releaseWL(435a2cb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  917): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  917): Waited long enough for: ServiceRecord{4363a110 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  917): acquireWL(4359c870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  917): n_update end
,D/UsbnetService(  917): BroadcastReceiver::onReceive+
D/UsbnetService(  917): onReceive BATTERY_CHANGED
D/UsbnetService(  917):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  917): BroadcastReceiver::onReceive-
D/PMS     (  917): releaseWL(4359c870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1596): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  917): updateBatteryInfo
D/PMS     (  917): runPSCheck
D/HtcPowerSaver(  917): Checking...
I/HtcPowerSaver(  917): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  917): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  917): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1525): service - handleMessage() stop self
,D/AutoSetting( 1525): service - onDestroy() END
,D/AutoSetting( 1525): service - handleMessage() quit looper
,D/Process (  917): killProcessQuiet, pid=4379
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  917): Killing 4379:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  917): Recipient 4379
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  917): acquireWL(425d4ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 917 1000 WorkSource{10027}
,V/AlarmManager(  917): sending alarm PendingIntent{437ad018: PendingIntentRecord{43401820 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=169640, Int=0
,D/PMS     (  917): releaseWL(425d4ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1246): switchBindHtcMsgCursor: null
,D/PMS     (  917): acquireWL(42ce6c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 917 1000 WorkSource{1000}
,V/AlarmManager(  917): sending alarm PendingIntent{41d5c740: PendingIntentRecord{42530cc0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=174543, Int=0
,D/PMS     (  917): acquireWL(4379efc0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 917 1000 null
,D/PMS     (  917): releaseWL(42ce6c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  917): getActiveNetworkInfo called by  (917/1000)
,D/PMS     (  917): acquireWL(439e5180): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 917 1000 null
,D/PMS     (  917): releaseWL(4379efc0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  917): releaseWL(439e5180): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  917): acquireWL(434f8ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  917): n_update end
,D/PMS     (  917): releaseWL(434f8ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  917): updateBatteryInfo
D/UsbnetService(  917): BroadcastReceiver::onReceive+
D/UsbnetService(  917): onReceive BATTERY_CHANGED
D/UsbnetService(  917):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  917): BroadcastReceiver::onReceive-
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1596): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  917): runPSCheck
D/HtcPowerSaver(  917): Checking...
I/HtcPowerSaver(  917): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  917): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  917): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1375): disconnect managed GoogleApiClient
,D/PMS     (  917): acquireWL(4345ffd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 917 1000 WorkSource{1000}
,V/AlarmManager(  917): sending alarm PendingIntent{422f1048: PendingIntentRecord{422cb6a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=198537, Int=0
I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  917): releaseWL(4345ffd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  917): acquireWL(434c7948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  917): n_update end
,D/UsbnetService(  917): BroadcastReceiver::onReceive+
D/UsbnetService(  917): onReceive BATTERY_CHANGED
D/UsbnetService(  917):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  917): BroadcastReceiver::onReceive-
,D/PMS     (  917): releaseWL(434c7948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1596): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=100
D/HtcPowerSaver(  917): updateBatteryInfo
D/PMS     (  917): runPSCheck
D/HtcPowerSaver(  917): Checking...
I/HtcPowerSaver(  917): >> updateStatus
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  917): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  917): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  917): acquireWL(44122798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  917): n_update end
,D/PMS     (  917): releaseWL(44122798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  917): BroadcastReceiver::onReceive+
D/UsbnetService(  917): onReceive BATTERY_CHANGED
D/UsbnetService(  917):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  917): BroadcastReceiver::onReceive-
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1596): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  917): updateBatteryInfo
D/PMS     (  917): runPSCheck
D/HtcPowerSaver(  917): Checking...
I/HtcPowerSaver(  917): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  917): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  917): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  917): acquireWL(44120280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 917 1000 WorkSource{1000}
,V/AlarmManager(  917): sending alarm PendingIntent{422f1048: PendingIntentRecord{422cb6a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=258537, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  917): releaseWL(44120280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  917): acquireWL(43d54dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  917): n_update end
D/UsbnetService(  917): BroadcastReceiver::onReceive+
D/UsbnetService(  917): onReceive BATTERY_CHANGED
D/UsbnetService(  917):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  917): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1596): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1596): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=100
D/HtcPowerSaver(  917): updateBatteryInfo
D/PMS     (  917): releaseWL(43d54dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  917): runPSCheck
D/HtcPowerSaver(  917): Checking...
I/HtcPowerSaver(  917): >> updateStatus
,I/HtcPowerSaver(  917): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  917): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4446): --= Surplus to requirements =--
I/jxcore-log( 4446): 
I/jxcore-log( 4446): ****TEST TOOK:  ms ****
I/jxcore-log( 4446): 
,I/jxcore-log( 4446): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4446): 
,E/cutils-trace( 4860): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4860): ====startRecUseTime====
D/htc.customization.log.level( 4860):  is 
,W/CustomizationLogLevel( 4860): Level value is invalid, use default level 2
,D/CustomizationManager( 4860):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 4860): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4860): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4860): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4860): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4860): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4860): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4860): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 4860): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4860): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4860): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4860): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4860): Parsing tag category name = system
,I/CustomizationCIDLoader( 4860): Parsing tag category name = application
I/CustomizationCIDLoader( 4860): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 4860): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4860): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4860): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4860): Parsing tag category name = Settings
D/CustomizationManager( 4860):  Read CID file spent 0.105 (s),
,D/CustomizationManager( 4860):  All configurations done spent 0.105 (s),
W/HtcNativeFlag( 4860): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4860): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4860): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4860): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  917): deletePackageAsUser: pkg=com.test.thalitest, pid=4860, uid=2000 user=0
,I/ActivityManager(  917): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  917): killProcessQuiet, pid=4446
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  917): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  917): Killing 4446:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  917):   Force finishing activity ActivityRecord{42453360 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  917): Copying FileAsset 0x62f730e8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/PackageSettings(  917): Skipping PackageSetting{42275260 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  917): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,E/JavaBinder(  917): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  917): !!! FAILED BINDER TRANSACTION !!!
,W/InputMethodManagerService(  917): Got RemoteException sending setActive(false) notification to pid 4446 uid 10389
D/DotMatrix( 1596): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1596): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1596): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
E/JavaBinder( 1215): !!! FAILED BINDER TRANSACTION !!!
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
,W/GeofencerStateMachine( 1228): Ignoring removeGeofence because network location is disabled.
D/PMS     (  917): acquireWL(437d7ef0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(437d7ef0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1304): Cleaning up data for package: com.test.thalitest
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  917):   Scheme: "sms"
,I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  917):   Scheme: "smsto"
,I/InputMethodManagerService(  917): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/WifiService(  917): Client connection lost with reason: 4
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  917): WIN DEATH: Window{41c3b0f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  917):   Scheme: "mms"
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1349): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/Launcher( 1280): Deferring update until onResume
,D/Launcher( 1280): waitUntilResume // bindAppsRemoved
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/[PluginManager]RegisterService( 1349): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1280): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "mmsto"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/IcingCorporaProvider( 2824): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "sms"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "smsto"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/ActivityManager(  917): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4876 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  917):   Scheme: "mms"
,I/PackageManager(  917):   Action: "android.intent.action.SENDTO"
I/PackageManager(  917):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  917):   Scheme: "mmsto"
I/PackageManager(  917): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,D/PhoneApp( 1246): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  917): acquireWL(4267fbd0): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): releaseWL(4267fbd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  917): acquireWL(41e154c8): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2824): UpdateCorporaTask done [took 330 ms] updated apps [took 330 ms] 
,W/PackageManager(  917): Unable to load service info ResolveInfo{43784760 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  917): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  917): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  917): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  917): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  917): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  917): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  917): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  917): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  917): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  917): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  917): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  917): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4876): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4876): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4876): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4876): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4876): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4876): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4876): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4876): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4876): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4876): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4876): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4876): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4876): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4876): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4876): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4876): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4876): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4876): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4876): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4876): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4876): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4876): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4876): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4876): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4876): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4876): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4876): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4876): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4876): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4876): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4876): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4876): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4876): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4876): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4876): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4876): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4876): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4876): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4876): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4876): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4876): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4876): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4876): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4876): threadid=11: thread exiting with uncaught exception (group=0x416fde30)
E/ActivityManager(  917): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4876): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4876): Process: com.google.android.apps.docs, PID: 4876
E/AndroidRuntime( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4876): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4876): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4876): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4876): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4876): 	at aho.run(AbstractDatabaseInstance.java:455)
D/Process ( 4876): killProcess, pid=4876
,D/Process ( 4876): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  917): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4895 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/DropBoxManagerService(  917): Can't write: system_app_crash
E/DropBoxManagerService(  917): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  917): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  917): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  917): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  917): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  917): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  917): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  917): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  917): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  917): 	... 5 more
I/ActivityManager(  917): Recipient 4876
I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  917): Process com.google.android.apps.docs (pid 4876) has died.
,W/ContextImpl( 4895): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4895): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
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
E/SQLiteDatabase( 4895): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4895): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4895): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4895): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4895): threadid=10: thread exiting with uncaught exception (group=0x416fde30)
I/ActivityManager(  917): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4908 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/AndroidRuntime( 4895): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4895): Process: com.android.keychain, PID: 4895
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
E/AndroidRuntime( 4895): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4895): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4895): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4895): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  917): App crashed! Process: com.android.keychain
D/ErrorReport(  917): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4895): killProcess, pid=4895
,D/Process ( 4895): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  917): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  917): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452278511269.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  917): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  917): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  917): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  917): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  917): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  917): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  917): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  917): 	... 4 more
,D/AppTag  ( 4908): getInstance(Context context)
I/ActivityManager(  917): Recipient 4895
I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  917): Process com.android.keychain (pid 4895) has died.
W/ActivityManager(  917): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/RemoteDisplayProvider(  917): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  917): start
,D/AppTag  ( 4908): getInstance(Context context)
,D/AppTag  ( 4908): onCreate()
,W/AtomicFile(  917): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/PMS     (  917): acquireWL(424a9998): PARTIAL_WAKE_LOCK  AsyncService 0x1 4083 10160 null
W/AppWidgetServiceImpl(  917): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  917): releaseWL(424a9998): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Process (  917): killProcessQuiet, pid=4010
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/dalvikvm( 4121): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  917): Killing 4010:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PackageBroadcastService( 2191): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2191): Clearing selected account for com.test.thalitest
I/ActivityManager(  917): Recipient 4010
I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ChimeraCfgMgr( 2191): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2191): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2191): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2191): Module APK com.google.android.play.games already loaded
I/ActivityManager(  917): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2191): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2191): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66697808
E/SQLiteLog( 2191): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2191): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cadb420
,W/dalvikvm( 2191): threadid=48: thread exiting with uncaught exception (group=0x416fde30)
,I/LocationSettingsChecker( 2191): Removing dialog suppression flag for package com.test.thalitest
,E/DriveAsyncService( 2191): disk I/O error (code 3850)
E/DriveAsyncService( 2191): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2191): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2191): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2191): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2191): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2191): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2191): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2191): 	at java.lang.Thread.run(Thread.java:864)
,E/AndroidRuntime( 2191): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2191): Process: com.google.android.gms, PID: 2191
E/AndroidRuntime( 2191): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2191): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2191): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2191): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2191): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2191): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2191): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2191): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2191): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2191): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2191): 	at java.lang.Thread.run(Thread.java:864)
,E/ActivityManager(  917): App crashed! Process: com.google.android.gms
,D/Process ( 2191): killProcess, pid=2191
,D/Process ( 2191): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  917): Can't write: system_app_crash
E/DropBoxManagerService(  917): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  917): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  917): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  917): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  917): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  917): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  917): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  917): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  917): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  917): 	... 5 more
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  917): handleWLDeath(41e154c8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  917): Client connection lost with reason: 4
,I/ActivityManager(  917): Recipient 2191
,I/ActivityManager(  917): Process com.google.android.gms (pid 2191) has died.
,W/ActivityManager(  917): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  917): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
,W/ActivityManager(  917): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10999ms
W/ActivityManager(  917): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
W/ActivityManager(  917): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
,I/ActivityManager(  917): Resuming delayed broadcast,
W/ActivityManager(  917): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20996ms
,W/ActivityManager(  917): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30995ms
,E/SQLiteLog( 1375): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1375): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x6400e288
,W/dalvikvm( 1375): threadid=1: thread exiting with uncaught exception (group=0x416fde30)
,E/AndroidRuntime( 1375): FATAL EXCEPTION: main
E/AndroidRuntime( 1375): Process: com.google.process.gapps, PID: 1375
E/AndroidRuntime( 1375): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1375): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1375): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1375): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1375): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1375): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1375): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1375): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1375): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1375): 	... 10 more
,E/ActivityManager(  917): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  917): Can't write: system_app_crash
E/DropBoxManagerService(  917): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  917): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  917): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  917): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  917): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  917): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  917): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  917): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  917): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  917): 	... 5 more
,D/Process ( 1375): killProcess, pid=1375
,D/Process ( 1375): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  917): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4938 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4938): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4938 dbg=false s=true
,I/DeviceManagement( 4938): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4938): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4938): WorkflowService: Starting workflow service
I/DeviceManagement( 4938): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5ee78] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4938): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4938): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4938): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4938): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  917): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4952 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4938): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4938): SessionStateController: Checking invariants...
,D/Documents( 4952): Loading roots for com.android.providers.downloads.documents
I/ActivityManager(  917): Recipient 1375
I/ActivityManager(  917): Process com.google.process.gapps (pid 1375) has died.
I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  917): Client connection lost with reason: 4
W/ActivityManager(  917): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30766ms
,E/SQLiteDatabase( 4952): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4952): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4952): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4952): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4952): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4952): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4952): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4952): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4952): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4952): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4952): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4952): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4952): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4952): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4952): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4952): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4952): threadid=1: thread exiting with uncaught exception (group=0x416fde30)
,D/Documents( 4952): Loading roots for com.android.externalstorage.documents
E/AndroidRuntime( 4952): FATAL EXCEPTION: main
E/AndroidRuntime( 4952): Process: com.android.documentsui, PID: 4952
E/AndroidRuntime( 4952): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4952): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4952): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4952): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4952): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4952): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4952): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4952): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4952): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4952): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4952): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4952): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4952): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4952): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4952): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4952): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4952): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4952): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4952): 	... 10 more
,I/ActivityManager(  917): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4966 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/Process (  917): killProcessQuiet, pid=4418
,I/ActivityManager(  917): Killing 4418:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  917): Recipient 4418
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ActivityManager(  917): App crashed! Process: com.android.documentsui
I/ActivityManager(  917): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4978 uid=10023 gids={50023, 1028, 1015, 1023}
D/ErrorReport(  917): HtcErrorReportManager Begin---add error logs to dropbox
,E/ErrorReport(  917): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  917): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452278511836.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  917): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  917): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  917): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  917): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  917): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  917): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  917): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  917): 	... 4 more
,D/Process (  917): killProcessQuiet, pid=4507
,D/Process (  917): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  917): Killing 4507:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process ( 4952): killProcess, pid=4952
,D/Process ( 4952): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  917): Recipient 4952
,I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteDatabase( 4938): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4938): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4938): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4938): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4938): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4938): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4938): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4938): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4938): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4938): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4938): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4938): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4938): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4938): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4938): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4938): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4938): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4938): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4938): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4938): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4938): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,I/ActivityManager(  917): Process com.android.documentsui (pid 4952) has died.
D/ExternalStorage( 4978): After updating volumes, found 1 active roots
W/dalvikvm( 4966): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 4966): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
E/SQLiteDatabase( 4938): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4938): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4938): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4938): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4938): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4938): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4938): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4938): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4938): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4938): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4938): 	at android.os.Looper.loop(Looper.java:157)
E/SQLi,teDatabase( 4938): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4966): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4966): install
I/MultiDex( 4966): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
W/DeviceManagement( 4938): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5ee78]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4938): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4938): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4938): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4938): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4938): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4938): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4938): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321),
W/DeviceManagement( 4938): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4938): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4938): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4938): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4938): WorkflowService: Stopping workflow service
I/MultiDex( 4966): loading existing secondary dex files
I/MultiDex( 4966): load found 3 secondary dex files,
I/MultiDex( 4966): install done
I/DisplayManagerService(  917): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  917): Recipient 4507
,D/WifiService(  917): Client connection lost with reason: 4,
,I/Prism.ItemManager( 1280): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1280): loadItems() com.htc.launcher.pageview.WidgetManager@41bc2d50 +
,I/Prism.WidgetManager( 1280): onLoadItems() +
,I/ActivityManager(  917): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=4995 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}

```
